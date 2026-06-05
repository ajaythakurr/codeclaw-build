# CodeClaw Build 🦅

A modern interactive CLI tool built with **Bun**, **Commander**, **Clack**, and **Figlet**.

CodeClaw helps developers bootstrap and manage projects through a clean terminal experience with interactive prompts and beautiful terminal UI.

---

## Features

* ⚡ Built with Bun
* 🎯 Command-based CLI using Commander
* 🎨 Interactive terminal UI with Clack
* 🖼️ ASCII banner rendering using Figlet
* 🌈 Custom shadow effects and styled output
* 🔌 Extensible architecture for future integrations
* 🤖 Telegram mode support (coming soon)

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/<your-username>/codeclaw-build.git
cd codeclaw-build
```

### Install Dependencies

```bash
bun install
```

### Link CLI Globally

```bash
bun link
bun link codeclaw-build
```

Verify installation:

```bash
codeclaw-build --help
```

---

## Usage

### Wakeup Command

Launch the interactive startup screen:

```bash
codeclaw-build wakeup
```

This command:

1. Displays the CodeClaw ASCII banner
2. Shows an interactive mode selector
3. Allows users to choose:

   * CLI Mode
   * Telegram Mode

---

## Project Structure

```text
codeclaw-build/
│
├── tui/
│   └── wakeup.ts
│
├── index.ts
├── package.json
├── tsconfig.json
├── bun.lock
└── README.md
```

---

## Tech Stack

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Bun        | Runtime & Package Manager |
| TypeScript | Type Safety               |
| Commander  | Command Parsing           |
| Clack      | Interactive Prompts       |
| Figlet     | ASCII Banner Rendering    |
| Chalk      | Terminal Styling          |

---

## Development

Run directly without linking:

```bash
bun run index.ts wakeup
```

Watch for changes:

```bash
bun --watch index.ts wakeup
```

---

## Roadmap

### Phase 1

* [x] CLI setup
* [x] Wakeup command
* [x] Interactive mode selection
* [x] Banner rendering

### Phase 2

* [ ] Project scaffolding
* [ ] Template generation
* [ ] Configuration wizard
* [ ] Plugin system

### Phase 3

* [ ] Telegram integration
* [ ] AI-powered workflows
* [ ] Deployment automation

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Commit your changes

```bash
git commit -m "feat: add amazing feature"
```

4. Push your branch

```bash
git push origin feature/amazing-feature
```

5. Open a Pull Request

---

## License

MIT License

---

Made with ❤️ using Bun and TypeScript.
