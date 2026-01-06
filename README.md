# Awesome Rust Python [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Python libraries and tools powered by Rust

Rust brings performance, safety, and concurrency to Python. This list showcases libraries that leverage Rust to supercharge Python applications.

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
- [Contributing](#contributing)

## Build Tools & Frameworks

Tools and frameworks for building Rust-powered Python extensions.

- **[inline-python](https://github.com/m-ou-se/inline-python)** - Inline Python code directly in your Rust code.
- **[maturin](https://github.com/PyO3/maturin)** - Build and publish Rust-based Python packages with minimal configuration. Supports multiple build backends and handles wheel building.
- **[pyo3-async-runtimes](https://github.com/PyO3/pyo3-async-runtimes)** - PyO3-based bridges between Python and Rust async runtimes.
- **[pyo3-file](https://github.com/omerbenamram/pyo3-file)** - A small helper library for working with python file-like objects with rust.
- **[pyo3-stub-gen](https://github.com/Jij-Inc/pyo3-stub-gen)** - Stub file (*.pyi) generator for PyO3.
- **[PyO3](https://github.com/PyO3/pyo3)** - Rust bindings for Python, including tools for creating native Python extension modules. The foundation for most Rust-Python projects.
- **[rustimport](https://github.com/mityax/rustimport)** - Import Rust source files directly from Python!
- **[RustPython](https://github.com/RustPython/RustPython)** - A Python Interpreter written in Rust.
- **[setuptools-rust](https://github.com/PyO3/setuptools-rust)** - Setuptools plugin for building Rust extensions, integrating seamlessly with existing Python packaging workflows.

## Data Processing

High-performance data processing and serialization libraries.

- **[jiter](https://github.com/pydantic/jiter)** - Fast iterable JSON parser.
- **[ormsgpack](https://github.com/aviramha/ormsgpack)** - Msgpack serialization/deserialization library for Python, written in Rust using PyO3.
- **[orjson](https://github.com/ijl/orjson)** - Fast, correct JSON library for Python. Serializes dataclass, datetime, numpy, and UUID instances natively.
- **[polars](https://github.com/pola-rs/polars)** - Lightning-fast DataFrame library with a Pandas-like API. Built entirely in Rust for maximum performance on large datasets.
- **[pydantic-core](https://github.com/pydantic/pydantic-core)** - Core validation logic for Pydantic v2, providing blazing-fast data validation and serialization.
- **[yaml-rs](https://github.com/lava-sh/yaml-rs)** - A High-Performance YAML v1.2 Parser for Python written in Rust.

## Development Tools

Developer tools that enhance Python development workflows.

- **[huak](https://github.com/cnpryer/huak)** - Experimental Python package manager.
- **[pylyzer](https://github.com/mtshiba/pylyzer)** - A fast, feature-rich static code analyzer & language server for Python.
- **[ruff](https://github.com/astral-sh/ruff)** - Extremely fast Python linter and code formatter, 10-100x faster than existing tools. Replaces Flake8, isort, and more.
- **[rumdl](https://github.com/rvben/rumdl)** - Markdown Linter and Formatter written in Rust.
- **[prek](https://github.com/j178/prek)** - A fast, Rust-based reimplementation of the pre-commit framework. ~10x faster with zero dependencies.
- **[ty](https://github.com/astral-sh/ty)** - An extremely fast Python type checker and language server, written in Rust.
- **[rye](https://github.com/astral-sh/rye)** - Experimental Python project management tool from the creator of Flask. Handles Python installations, dependencies, and virtualenvs.
- **[uv](https://github.com/astral-sh/uv)** - Ultra-fast Python package installer and resolver, designed as a drop-in replacement for pip and pip-tools.

## Web & Networking

Web servers, networking libraries, and cryptographic tools.

- **[cryptography](https://github.com/pyca/cryptography)** - Cryptographic recipes and primitives for Python. Core cryptographic operations implemented in Rust for security and performance.
- **[granian](https://github.com/emmett-framework/granian)** - High-performance ASGI/WSGI server built with Rust, supporting HTTP/1, HTTP/2, and WebSockets.
- **[httparse](https://github.com/adriangb/httparse)** - Python wrapper for Rust's httparse HTTP parser.
- **[nh3](https://github.com/messense/nh3)** - Python binding to Ammonia HTML sanitizer Rust crate.
- **[pyreqwest](https://github.com/MarkusSintonen/pyreqwest)** - Fast Python HTTP client based on Rust reqwest.
- **[pyrtls](https://github.com/djc/pyrtls)** - rustls-based modern TLS for Python.
- **[rloop](https://github.com/gi0baro/rloop)** - An AsyncIO event loop implemented in Rust.
- **[rnet](https://github.com/0x676e67/rnet)** - An ergonomic Python HTTP Client with TLS fingerprint.
- **[Robyn](https://github.com/sparckles/Robyn)** - Robyn is a Super Fast Async Python Web Framework with a Rust runtime.

## Machine Learning & AI

Tools for machine learning, NLP, and AI applications.

- **[chroma](https://github.com/chroma-core/chroma)** - Open-source search and retrieval database for AI applications.
- **[safetensors](https://github.com/huggingface/safetensors)** - Safe and fast tensor serialization format. Prevents arbitrary code execution and enables zero-copy deserialization.
- **[tokenizers](https://github.com/huggingface/tokenizers)** - Fast tokenizers for modern NLP pipelines from Hugging Face. Provides extremely fast training, tokenization, and encoding.

## Performance & Caching

High-performance caching and data structure libraries.

- **[cachebox](https://github.com/awolverp/cachebox)** - The fastest memoizing and caching Python library written in Rust.
- **[fastbloom](https://github.com/yankun1992/fastbloom)** - A fast bloom filter implemented by Rust for Python! 10x faster than pybloom!
- **[moka-py](https://github.com/deliro/moka-py)** - A high performance caching library for Python written in Rust.
- **[rbloom](https://github.com/KenanHanke/rbloom)** - A fast, simple and lightweight Bloom filter library for Python, implemented in Rust.

## Text Processing & Parsing

Libraries for text processing, parsing, and manipulation.

- **[pyromark](https://github.com/monosans/pyromark)** - Blazingly fast Markdown parser for Python written in Rust.
- **[Python-Regex](https://github.com/litmus-web/Python-Regex)** - A port of the Rust regex library to python for super speed linear matching.
- **[regex-rs](https://github.com/circuitsacul/regex-rs)** - Python bindings for the rust regex crate.
- **[tantivy-py](https://github.com/quickwit-oss/tantivy-py)** - Python bindings for Tantivy full-text search engine.

## Utilities

Miscellaneous utility libraries.

- **[geohashr](https://github.com/gi0baro/geohashr)** - Just another Python geohashing library.
- **[hexora](https://github.com/rushter/hexora)** - Static analysis of malicious Python code.
- **[jsrun](https://github.com/imfing/jsrun)** - Modern JavaScript runtime in Python, powered by V8 and bridged by Rust.
- **[PyDomainExtractor](https://github.com/Intsights/PyDomainExtractor)** - A blazingly fast domain extraction library written in Rust.
- **[pythonize](https://github.com/davidhewitt/pythonize)** - Python serialization library for Rust types.
- **[result](https://github.com/rustedpy/result)** - A simple Rust like Result type for Python 3. Fully type annotated.
- **[rtoml](https://github.com/samuelcolvin/rtoml)** - A fast TOML library for python implemented in rust.
- **[ryaml](https://github.com/emmatyping/ryaml)** - Python yaml library using Rust.
- **[tonio](https://github.com/gi0baro/tonio)** - A multi-threaded async runtime for Python.
- **[uuid-utils](https://github.com/aminalaee/uuid-utils)** - Python bindings to Rust UUID.
- **[whenever](https://github.com/ariebovenberg/whenever)** - Modern datetime library for Python.
- **[zensical](https://github.com/zensical/zensical)** - A modern static site generator by the Material for MkDocs team.

## Game Development

Game engines and frameworks.

- **[pyxel](https://github.com/kitao/pyxel)** - A retro game engine for Python.

## Resources

### Learning Materials

- **[PyO3 User Guide](https://pyo3.rs/)** - Comprehensive guide to building Python extensions with Rust
- **[Calling Rust from Python](https://blog.frankel.ch/rust-from-python/)** - Tutorial series on Rust-Python integration
- **[Speed Up Your Python with Rust](https://developers.redhat.com/blog/2017/11/16/speed-python-using-rust)** - Red Hat's guide to optimizing Python with Rust

### Articles & Blog Posts

- **[Why Polars uses Rust](https://pola.rs/posts/why-rust/)** - Insights into choosing Rust for data processing
- **[Pydantic V2 Plan](https://pydantic.dev/articles/pydantic-v2)** - How Rust powers Pydantic's performance improvements
- **[Ruff: One Tool to Rule Them All](https://astral.sh/blog/ruff-v0.1.0)** - The story behind building a fast Python linter in Rust

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
