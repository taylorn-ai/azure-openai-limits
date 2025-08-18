# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-08-19

### Added

- Initial release of azure-openai-limits package
- Support for GPT-3.5, GPT-4, GPT-4o, GPT-5, O1, O3, and O4 model families
- Command-line interface with `list` and `show` commands
- Python API with functions: `get_limits()`, `context_limit()`, `output_limit()`, `model_exists()`, `list_models()`, `list_versions()`
- Comprehensive error handling with helpful error messages
- Version fallback support (falls back to default when specific version not found)
- Complete test suite with 14+ test cases
- Type hints and mypy support
- Static model limits data sourced from Microsoft documentation

### Features

- Support for 28+ Azure OpenAI models and their versions
- Context and output token limits for each model version
- Graceful fallback to default version when specific version not found
- Helpful error messages listing available models/versions
- CLI with JSON output format
- Comprehensive API documentation

[0.1.0]: https://github.com/taylorn-ai/azure-openai-limits/releases/tag/v0.1.0
