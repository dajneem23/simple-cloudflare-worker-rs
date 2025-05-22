# Simple Cloudflare Worker in Rust 🦀☁️

This project is a minimal example of a Cloudflare Worker written in Rust using WebAssembly.

## 🛠 Tech Stack

- [Rust](https://www.rust-lang.org/)
- [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen)
- [Cloudflare Workers](https://workers.cloudflare.com/)
- [Wrangler](https://developers.cloudflare.com/workers/wrangler/)

---

## 🚀 Getting Started

### 1. Install Rust and Tools

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
cargo install wasm-pack
npm install -g wrangler
```

### 2.  Build the Project

```bash

    npx wrangler build 
```

### 3.  Preview the Project

```bash
    npx wrangler dev
```

### 4.  Publish the Project

```bash
    npx wrangler deploy
```