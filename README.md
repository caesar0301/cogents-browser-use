# cogents_bu

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
