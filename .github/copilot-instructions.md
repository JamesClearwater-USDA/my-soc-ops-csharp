# Copilot Workspace Instructions

## Mandatory Development Checklist

Before considering a change complete, run and report all three checks:

- [ ] Lint: `dotnet format SocOps/SocOps.csproj --verify-no-changes`
- [ ] Build: `dotnet build SocOps/SocOps.csproj`
- [ ] Test: `dotnet test`

If no test project exists, run the command and report that tests are unavailable. For UI changes, also verify the affected route at `http://localhost:5166`.

## Project

Soc Ops is a Blazor WebAssembly social bingo game targeting .NET 10. Game UI is in `SocOps/Components` and `SocOps/Pages`; domain models are in `Models`, rules and state are in `Services`, and questions are in `Data`.

Use `dotnet run --project SocOps/SocOps.csproj` to start the development server. Do not modify `.solutions/`, generated `bin/` or `obj/` output, secrets, or unrelated files unless explicitly requested.

## Implementation Rules

- Keep game rules in services/models, not Razor markup.
- Preserve `BingoGameService.OnStateChanged` event updates and dispose subscriptions in components.
- Use focused components with parameters and callbacks; use PascalCase for public C# members and descriptive local names.
- Prefer existing utilities in `SocOps/wwwroot/css/app.css`; follow the scoped CSS and frontend instructions in `.github/instructions/`.
- Preserve responsive layout, semantic HTML, accessible focus states, and usable button labels.
- Keep changes minimal and avoid unrelated refactors.
