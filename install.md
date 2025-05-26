## 安装准备
- curl https://sh.rustup.rs -sSf | sh
- . "$HOME/.cargo/env"
- cargo install cargo-shuttle --vers 0.47.0
- cargo install dioxus-cli -- mac风扇响个不同, cpu达到100度 
- rustup target add wasm32-unknown-unknown
- cargo install cargo-watch
- cargo install cargo-make

## 运行
- 根目录下, cargo shuttle run
- front目录下,  dx serve --platform web

## 资源
- https://github.com/Bechma/realworld-actix-fullstack
- https://github.com/fairingrey/actix-realworld-example-app
- https://github.com/jetli/rust-yew-realworld-example-app
- https://github.com/davidpdrsn/realworld-axum-sqlx