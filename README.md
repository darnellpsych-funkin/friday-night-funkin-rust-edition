# Friday Night Funkin' Rust Edition

Reconstrucción de Friday Night Funkin' con Rust compilado a WebAssembly.

Proyecto de fan, no oficial. Friday Night Funkin' pertenece a The Funkin' Crew. Los assets de personajes provienen de Bambi-Slice y conservan sus licencias originales.

## Estado

- En desarrollo.
- Primer módulo en Rust: juicio de notas (Sick, Good, Bad, Shit y Fallo). Versión de prueba en el repo [friday-night-funkin-javascript-edition](https://github.com/darnellpsych-funkin/friday-night-funkin-javascript-edition), rama `wip/rust-judge-dad-gf`.

## Compilar

```
rustup target add wasm32-unknown-unknown
cargo build --release --target wasm32-unknown-unknown
```

La página de presentación está en `docs/` y se publica con GitHub Pages desde la rama `main`.
