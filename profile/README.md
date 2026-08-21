# wlrgo

**Whole Lotta Rust - GOluxe version** — Rust-like libraries for Go.

Ports of familiar Rust std types, as close as Go allows:

- [`option`](https://github.com/wlrgo/option) — `Option[T]` for values that may be absent;
- [`result`](https://github.com/wlrgo/result) — `Result[T, E]` for a value or an error.

Conversions that would couple those packages live separately:

- [`optres`](https://github.com/wlrgo/optres) — Option/Result conversions (`Ok`, `OkOr`, transpose).
