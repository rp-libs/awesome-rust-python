<div align="center">

# Awesome Rust Python [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Python libraries and tools powered by Rust.

</div>

> Rust brings performance, safety, and concurrency to Python. This list showcases libraries that leverage Rust to supercharge Python applications.

---

## Contents

- [Build Tools & Frameworks](#build-tools--frameworks)
- [Data Processing](#data-processing)
- [Development Tools](#development-tools)
- [Web & Networking](#web--networking)
- [Machine Learning & AI](#machine-learning--ai)
- [Performance & Caching](#performance--caching)
- [Text Processing & Parsing](#text-processing--parsing)
- [Utilities](#utilities)
- [Game Development](#game-development)
- [Resources](#resources)

---

## Build Tools & Frameworks

Tools and frameworks for building Rust-powered Python extensions.

- [cpython](https://github.com/Rust-for-CPython/cpython) - Experimental Rust-for-CPython branch focused on bringing Rust into CPython internals.
- [inline-python](https://github.com/m-ou-se/inline-python) - Inline Python code directly in your Rust code.
- [maturin](https://github.com/PyO3/maturin) - Build and publish Rust-based Python packages with minimal configuration.
- [pyo3-async-runtimes](https://github.com/PyO3/pyo3-async-runtimes) - PyO3-based bridges between Python and Rust async runtimes.
- [pyo3-file](https://github.com/omerbenamram/pyo3-file) - Helper library for working with Python file-like objects with Rust.
- [pyo3-stub-gen](https://github.com/Jij-Inc/pyo3-stub-gen) - Stub file (*.pyi) generator for PyO3.
- [PyO3](https://github.com/PyO3/pyo3) - Rust bindings for Python, including tools for creating native Python extension modules.
- [rustimport](https://github.com/mityax/rustimport) - Import Rust source files directly from Python.
- [RustPython](https://github.com/RustPython/RustPython) - Python Interpreter written in Rust.
- [setuptools-rust](https://github.com/PyO3/setuptools-rust) - Setuptools plugin for building Rust extensions.

## Data Processing

High-performance data processing and serialization libraries.

- [delta-rs](https://github.com/delta-io/delta-rs) - Native Rust library for Delta Lake with Python bindings.
- [jiter](https://github.com/pydantic/jiter) - Fast iterable JSON parser.
- [ormsgpack](https://github.com/ormsgpack/ormsgpack) - MessagePack serialization library for Python written in Rust.
- [orjson](https://github.com/ijl/orjson) - Fast, correct JSON library.
- [polars](https://github.com/pola-rs/polars) - DataFrame library with a Pandas-like API.
- [pydantic-core](https://github.com/pydantic/pydantic-core) - Core validation logic for Pydantic v2.
- [rustworkx](https://github.com/Qiskit/rustworkx) - High-performance Python graph library implemented in Rust.
- [statguard](https://github.com/Mullassery/statguard) - Declarative data quality and validation library — schema checks, drift detection (PSI + KS), anomaly detection, and native Delta Lake/Iceberg support. 13–25× faster than pandera and Great Expectations.
- [StreamXL](https://github.com/Mullassery/StreamXL) - Streaming XLSX reader that processes large Excel files row-by-row at constant memory usage. 4–5× faster than openpyxl with PyO3 bindings.
- [yaml-rs](https://github.com/lava-sh/yaml-rs) - High-performance YAML v1.2 parser.

## Development Tools

Developer tools that enhance Python development workflows.

- [huak](https://github.com/cnpryer/huak) - Python package manager.
- [prek](https://github.com/j178/prek) - Fast reimplementation of the pre-commit framework.
- [pylyzer](https://github.com/mtshiba/pylyzer) - Static code analyzer and language server.
- [ruff](https://github.com/astral-sh/ruff) - Extremely fast Python linter and code formatter.
- [rumdl](https://github.com/rvben/rumdl) - Markdown linter and formatter.
- [rye](https://github.com/astral-sh/rye) - Python project management tool.
- [ty](https://github.com/astral-sh/ty) - Python type checker and language server.
- [uv](https://github.com/astral-sh/uv) - Python package installer and resolver.

## Web & Networking

Web servers, networking libraries, and cryptographic tools.

- [BustAPI](https://github.com/GrandpaEJ/BustAPI) - High-performance Python web framework.
- [compio-py](https://github.com/compio-rs/compio-py) - AsyncIO event loop using Rust compio.
- [cryptography](https://github.com/pyca/cryptography) - Cryptographic recipes and primitives.
- [django-bolt](https://github.com/FarhanAliRaza/django-bolt) - Rust-powered API framework for Django.
- [granian](https://github.com/emmett-framework/granian) - High-performance ASGI/WSGI server.
- [httparse](https://github.com/adriangb/httparse) - Wrapper for the httparse HTTP parser.
- [leviathan](https://github.com/kython28/leviathan) - Lightning-fast event loop for Python asyncio.
- [nh3](https://github.com/messense/nh3) - Binding to Ammonia HTML sanitizer.
- [pyreqwest](https://github.com/MarkusSintonen/pyreqwest) - HTTP client based on reqwest.
- [pyrtls](https://github.com/djc/pyrtls) - Rustls-based TLS library.
- [rloop](https://github.com/gi0baro/rloop) - AsyncIO event loop.
- [rnet](https://github.com/0x676e67/rnet) - HTTP client with TLS fingerprinting.
- [Robyn](https://github.com/sparckles/Robyn) - Async web framework with a Rust runtime.

## Machine Learning & AI

Tools for machine learning, NLP, and AI applications.

- [ClusterAudienceKit](https://github.com/Mullassery/ClusterAudienceKit) - Python library for customer segmentation in Martech pipelines — RFM analysis, clustering, streaming updates, and drift detection in a single pip install.
- [boxlite](https://github.com/boxlite-ai/boxlite) - Local-first sandbox for AI agents.
- [chroma](https://github.com/chroma-core/chroma) - Search and retrieval database for AI applications.
- [monty](https://github.com/pydantic/monty) - Minimal secure Python interpreter for AI workloads.
- [safetensors](https://github.com/huggingface/safetensors) - Safe and fast tensor serialization format.
- [tokenizers](https://github.com/huggingface/tokenizers) - Fast tokenizers for NLP pipelines.

## Performance & Caching

High-performance caching and data structure libraries.

- [cachebox](https://github.com/awolverp/cachebox) - Memoizing and caching library.
- [fastbloom](https://github.com/yankun1992/fastbloom) - Bloom filter implementation.
- [moka-py](https://github.com/deliro/moka-py) - High performance caching library.
- [rbloom](https://github.com/KenanHanke/rbloom) - Bloom filter library.

## Text Processing & Parsing

Libraries for text processing, parsing, and manipulation.

- [comrak](https://github.com/lmmx/comrak) - Python bindings for Comrak CommonMark/GFM parser.
- [Python-Regex](https://github.com/litmus-web/Python-Regex) - Port of the Rust regex library.
- [pyromark](https://github.com/monosans/pyromark) - Markdown parser.
- [regex-rs](https://github.com/circuitsacul/regex-rs) - Bindings for the regex crate.
- [tantivy-py](https://github.com/quickwit-oss/tantivy-py) - Bindings for Tantivy full-text search engine.

## Utilities

Miscellaneous utility libraries.

- [geohashr](https://github.com/gi0baro/geohashr) - Geohashing library.
- [hexora](https://github.com/rushter/hexora) - Static analysis of malicious code.
- [imgrs](https://github.com/GrandpaEJ/imgrs) - High-performance image processing library for Python powered by Rust.
- [oxyde](https://github.com/mr-fatalyst/oxyde) - Type-safe async ORM with a high-performance Rust core.
- [jsrun](https://github.com/imfing/jsrun) - JavaScript runtime powered by V8.
- [magic-rs](https://github.com/rp-libs/magic-rs) - Dependency-free file type detection backed by Rust.
- [PyDomainExtractor](https://github.com/Intsights/PyDomainExtractor) - Domain extraction library.
- [pythonize](https://github.com/davidhewitt/pythonize) - Serialization library for Rust types.
- [ratatui-py](https://github.com/holo-q/ratatui-py) - Python bindings for Ratatui (Rust TUI) via FFI.
- [result](https://github.com/rustedpy/result) - Rust-like Result type.
- [rtoml](https://github.com/samuelcolvin/rtoml) - TOML library.
- [ryaml](https://github.com/emmatyping/ryaml) - YAML library.
- [tonio](https://github.com/gi0baro/tonio) - Multi-threaded async runtime.
- [ulid-rs-py](https://github.com/rp-libs/ulid-rs-py) - Fast ULID implementation for Python.
- [uuid-utils](https://github.com/aminalaee/uuid-utils) - Bindings to Rust UUID.
- [whenever](https://github.com/ariebovenberg/whenever) - Modern datetime library.
- [zensical](https://github.com/zensical/zensical) - Static site generator.

## Game Development

Game engines and frameworks.

- [pyxel](https://github.com/kitao/pyxel) - Retro game engine.

## Resources

### Learning Materials

- [Calling Rust from Python](https://blog.frankel.ch/rust-from-python/) - Tutorial series on Rust-Python integration.
- [PyO3 User Guide](https://pyo3.rs/) - Comprehensive guide to building Python extensions with Rust.
- [Speed Up Your Python with Rust](https://developers.redhat.com/blog/2017/11/16/speed-python-using-rust) - Guide to optimizing Python with Rust.

### Articles & Blog Posts

- [Pydantic V2 Plan](https://pydantic.dev/articles/pydantic-v2) - How Rust powers Pydantic's performance improvements.
- [Ruff: One Tool to Rule Them All](https://astral.sh/blog/ruff-v0.1.0) - The story behind building a fast Python linter in Rust.
- [Why Polars uses Rust](https://pola.rs/posts/why-rust/) - Insights into choosing Rust for data processing.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
