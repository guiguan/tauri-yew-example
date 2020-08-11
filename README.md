# tauri-yew-example

Hello world example for Tauri + Yew

- [yew-wasm-pack-template](https://github.com/yewstack/yew-wasm-pack-template)

## Usage

Tested with:
- node: v12.16.3
- osx: 10.15.6

### Dev

#### Master setup

1. In root directory: `npm install`

#### Rust (wasm) end

1. Setup: `cd src-app && npm install`
2. Run webpack dev server: `npm run start:dev`
3. The app should available at `http://localhost:4000`

#### Tauri end

1. Setup: `cd src-tauri && npm install`
2. Run tauri dev server: in root directory `npm run tauri dev`
3. The to-do app should launch now

### Release

1. Build rust app to `./dist`: `cd src-app && npm run build`
2. Build tauri app: in root directory `npm run tauri build`
3. The generated to-do app should be in `src-tauri/target/release/bundle`
