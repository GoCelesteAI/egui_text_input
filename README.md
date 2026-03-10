# Greeting Form — Learn egui in Neovim (Episode 4)

A greeting form built with Rust and egui. Type a name and see a personalized greeting appear instantly.

## What You'll Build

- Text input with `text_edit_singleline()`
- `String` state to hold user input
- `&mut` binding for live updates
- Conditional display with `is_empty()`

## Prerequisites

- Rust installed ([rustup.rs](https://rustup.rs))
- eframe 0.31

## Run

```bash
cargo run
```

## Key Concepts

| Concept | Code |
|---------|------|
| Text input | `ui.text_edit_singleline(&mut self.name)` |
| String state | `name: String` in App struct |
| Mutable binding | `&mut self.name` |
| Empty check | `!self.name.is_empty()` |
| Format greeting | `format!("Hello, {}!", self.name)` |

## Series

**Learn egui in Neovim** — Build desktop apps with Rust and egui, coded entirely in Neovim.

Taught by [CelesteAI](https://github.com/GoCelesteAI)
