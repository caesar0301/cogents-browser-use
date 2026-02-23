# cogents-browser-use

>  🗣️🗣️🗣️ This project has been archived since 2026-02 and contributed to [Mirasoth's Noesium](https://github.com/mirasoth/noesium/tree/main/noesium/agents/browser_use).

[![CI](https://github.com/caesar0301/cogents-browser-use/actions/workflows/ci.yml/badge.svg)](https://github.com/caesar0301/cogents-browser-use/actions/workflows/ci.yml)
[![PyPI version](https://img.shields.io/pypi/v/cogents-browser-use.svg)](https://pypi.org/project/cogents-browser-use/)

AI-powered browser automation adapted from browser-use on the Cogents stack.

## Installation

```bash
pip install -e ".[dev]"
```

## Quick Start

```python
from cogents_bu import Agent, BrowserProfile

agent = Agent(
    task="Your task description here",
    max_steps=50,
    browser_profile=BrowserProfile(headless=False)
)
await agent.run()
```

See [examples/](examples/) for more usage examples.

## Development

```bash
make install    # Install dependencies
make test       # Run tests
make format     # Format code
make lint       # Run linters
```

## License

MIT License - see [LICENSE](LICENSE) file for details.
