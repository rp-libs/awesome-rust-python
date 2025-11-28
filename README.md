# Awesome Rust Python [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Python libraries and tools powered by Rust

Rust brings performance, safety, and concurrency to Python. This list showcases libraries that leverage Rust to supercharge Python applications.

## Contents

- [Build Tools & Frameworks](#build-tools--frameworks)
- [Data Processing](#data-processing)
- [Development Tools](#development-tools)
- [Web & Networking](#web--networking)
- [Machine Learning & AI](#machine-learning--ai)
- [Resources](#resources)
- [Contributing](#contributing)

## Build Tools & Frameworks

Tools and frameworks for building Rust-powered Python extensions.

- **[PyO3](https://github.com/PyO3/pyo3)** - Rust bindings for Python, including tools for creating native Python extension modules. The foundation for most Rust-Python projects.
- **[maturin](https://github.com/PyO3/maturin)** - Build and publish Rust-based Python packages with minimal configuration. Supports multiple build backends and handles wheel building.
- **[setuptools-rust](https://github.com/PyO3/setuptools-rust)** - Setuptools plugin for building Rust extensions, integrating seamlessly with existing Python packaging workflows.

## Data Processing

High-performance data processing and serialization libraries.

- **[polars](https://github.com/pola-rs/polars)** - Lightning-fast DataFrame library with a Pandas-like API. Built entirely in Rust for maximum performance on large datasets.
- **[orjson](https://github.com/ijl/orjson)** - Fast, correct JSON library for Python. Serializes dataclass, datetime, numpy, and UUID instances natively.
- **[pydantic-core](https://github.com/pydantic/pydantic-core)** - Core validation logic for Pydantic v2, providing blazing-fast data validation and serialization.

## Development Tools

Developer tools that enhance Python development workflows.

- **[ruff](https://github.com/astral-sh/ruff)** - Extremely fast Python linter and code formatter, 10-100x faster than existing tools. Replaces Flake8, isort, and more.
- **[uv](https://github.com/astral-sh/uv)** - Ultra-fast Python package installer and resolver, designed as a drop-in replacement for pip and pip-tools.
- **[rye](https://github.com/astral-sh/rye)** - Experimental Python project management tool from the creator of Flask. Handles Python installations, dependencies, and virtualenvs.

## Web & Networking

Web servers, networking libraries, and cryptographic tools.

- **[granian](https://github.com/emmett-framework/granian)** - High-performance ASGI/WSGI server built with Rust, supporting HTTP/1, HTTP/2, and WebSockets.
- **[cryptography](https://github.com/pyca/cryptography)** - Cryptographic recipes and primitives for Python. Core cryptographic operations implemented in Rust for security and performance.

## Machine Learning & AI

Tools for machine learning, NLP, and AI applications.

- **[tokenizers](https://github.com/huggingface/tokenizers)** - Fast tokenizers for modern NLP pipelines from Hugging Face. Provides extremely fast training, tokenization, and encoding.
- **[safetensors](https://github.com/huggingface/safetensors)** - Safe and fast tensor serialization format. Prevents arbitrary code execution and enables zero-copy deserialization.

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
