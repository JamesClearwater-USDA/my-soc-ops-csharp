<div align="center">

# 🎯 Soc Ops

### Break the ice. Meet the room. Call BINGO.

**Soc Ops turns any in-person gathering into a fast, friendly social challenge.**
Find people who match the prompts on your card, mark five in a row, and celebrate the connections you made along the way.

[**🎮 Play now**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) · [**📚 Start the lab**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) · [**🤝 Contribute**](CONTRIBUTING.md)

[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WebAssembly](https://img.shields.io/badge/Blazor-WebAssembly-702AF7?logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![MIT License](https://img.shields.io/badge/license-MIT-2F855A)](LICENSE)

🌐 **English** · [Português (BR)](README.pt_BR.md) · [Español](README.es.md)

</div>

---

## A conversation starter disguised as a game

Soc Ops gives every player a 5×5 card filled with conversation prompts. Walk around, meet someone who matches a square, and tap it to mark your progress. Complete a row, column, or diagonal to win.

### How to play

1. **Start a card** — open the game and tap **Start Game**.
2. **Meet someone** — find a person who matches one of the prompts.
3. **Mark the square** — tap it to record your match.
4. **Get five in a row** — complete a line and call **BINGO!**

Perfect for meetups, workshops, conferences, classrooms, and team events.

## ✨ What is inside

- 📱 A responsive, touch-friendly bingo board
- 🎉 Automatic row, column, and diagonal win detection
- 🔀 A fresh randomized card for every game
- ⚡ A lightweight Blazor WebAssembly experience
- 🧭 A hands-on GitHub Copilot agent lab built around the app

## 🚀 Run it locally

### Prerequisite

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or later

From the repository root:

```bash
dotnet run --project SocOps/SocOps.csproj
```

Open [http://localhost:5166](http://localhost:5166), then start meeting people.

To create a production build:

```bash
dotnet build SocOps/SocOps.csproj
```

> Prefer a cloud environment? Create a GitHub Codespace from **Code → Codespaces → Create codespace on main**, then run the same command.

## 🧪 Learn by building

This repository is also a guided lab for learning how to collaborate with GitHub Copilot agents. Follow the journey online or read the guides in [`workshop/`](workshop/) offline.

| Part | Mission |
|:---:|---|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Get oriented with the overview and checklist |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Set up the project and practice context engineering |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Shape the experience with design-first frontend work |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Create a custom Quiz Master agent |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Coordinate multi-agent development |

## 🗺️ Project map

```text
SocOps/
├── Components/   # Reusable game UI
├── Data/         # Bingo questions
├── Models/       # Board and game-state models
├── Pages/        # Routable Blazor pages
├── Services/     # Game state and bingo rules
└── wwwroot/      # Static assets and styles
```

## 🤝 Join in

Ideas, fixes, and new prompts are welcome. Read the [contribution guide](CONTRIBUTING.md), follow the [Code of Conduct](CODE_OF_CONDUCT.md), and open a pull request.

Soc Ops is released under the [MIT License](LICENSE). Deployments to GitHub Pages run automatically when changes land on `main`.
