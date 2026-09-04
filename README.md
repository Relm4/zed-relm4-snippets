# Relm4 Snippets for Zed

This extension for [Zed](https://zed.dev) adds code snippets for [Relm4](https://relm4.org).

It's the Zed counterpart to [vscode-relm4-snippets](https://github.com/Relm4/vscode-relm4-snippets).

## Usage

| Syntax                         | Description                                 |
| ------------------------------- | -------------------------------------------- |
| `relm-component`                | Create a new `Component` widget              |
| `relm-async-component`          | Create a new `AsyncComponent` widget         |
| `relm-simple-component`         | Create a new `SimpleComponent` widget        |
| `relm-simple-async-component`   | Create a new `SimpleAsyncComponent` widget   |
| `relm-factory`                  | Create a new `Factory` widget                |
| `relm-async-factory`            | Create a new `AsyncFactory` widget           |
| `relm-template`                 | Create a new `WidgetTemplate` widget         |
| `relm-worker`                   | Create a new `Worker` structure              |

## Developing locally

This extension is pure snippets, so no Rust/WASM build step is required.

1. Open Zed's extensions page (`zed: extensions`).
2. Click **Install Dev Extension** and select this repository's directory.

## Publishing

Once ready, this extension is submitted to the [Zed Extension Registry](https://github.com/zed-industries/extensions) as documented in their [Publishing Guide](https://zed.dev/docs/extensions/developing-extensions), by adding it as a submodule and an entry in that repo's `extensions.toml`.
