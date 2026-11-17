# MiniPdf for Rust

[Full guide (English)](../README.md)

## Quick start

```bash
cargo add minipdf
cargo install minipdf-cli
```

```rust
minipdf::convert_to_pdf("report.docx", "report.pdf")?;
```

```bash
minipdf report.docx -o report.pdf
```

Pour l'utilisation, consultez le [guide Rust](../README.md).

## Visual results

- [XLSX](https://mini-software.github.io/minipdf-web-page/?language=rust&suite=classic&format=xlsx)
- [DOCX](https://mini-software.github.io/minipdf-web-page/?language=rust&suite=classic&format=docx)

## License

[Apache License 2.0](../LICENSE).
