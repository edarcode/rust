# Instalación

Se utiliza **rustup** para instalar y gestionar las versiones de Rust. Si usa **macOS**, **GNU/Linux** u otra variante de **Unix** ejecute:

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Rust se actualiza constantemente. Puede actualizar con:

```
rustup update
```

# Cargo

Cuando instalas **rustup** también obtienes la última versión estable de la herramienta de compilación y gestión de paquetes de **rust**, conocida como **cargo**.

Para verificar que tienes Rust y Cargo instalados:

```
cargo --version
```

Para Desinstalar **rust** y **rustup**:

```
$ rustup self uninstall
```

Cargo hace un montón de cosas:

- construye tu proyecto con:

  ```
  cargo build
  ```

- ejecuta tu proyecto con:
  ```
    cargo run
  ```
- ejecuta los tests de tu proyecto con:
  ```
  cargo test
  ```
- genera la documentación de tu proyecto con:
  ```
  cargo doc
  ```
- publica una biblioteca en crates.io con:
  ```
  cargo publish
  ```
