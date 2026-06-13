# Multimodal-OCR

## Overview

Multimodal-OCR is a Gradio application for OCR and vision-oriented prompting across multiple vision-language models. The app accepts a single uploaded image and a single text instruction, runs the selected backend, and streams the generated text output back into the UI.

## Tech Stack

- Python (requirements.txt based)

## Repository Structure

- `.env.example`
- `app.py`
- `CHANGELOG.md`
- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- `examples/`
- `LICENSE`
- `pre-requirements.txt`
- `README.md`
- `requirements.txt`
- `SECURITY.md`

## Getting Started

### Prerequisites

- Git
- Runtime dependencies for this project's stack

### Installation

```bash
uv venv
uv pip install -r requirements.txt
```

## Usage

Run the primary app with `uv run app.py`.

## Testing

Add tests under `tests/` and run the repository's configured test command.

## Security

Please review [SECURITY.md](SECURITY.md) for reporting and handling security issues.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before opening issues or pull requests.

## Changelog

Ongoing changes are tracked in [CHANGELOG.md](CHANGELOG.md).

## License

This project is licensed under the terms described in [LICENSE](LICENSE).
