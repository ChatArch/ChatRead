# Python Interface Tree

The current version contains package identity and the CLI skeleton only. No reading APIs are implemented yet.

```text
chatread
├── __init__.py  # __version__
└── cli.py       # Click main entry point
```

```python
from chatread import __version__
```

Future domain capabilities should expose importable Python functions or classes, with thin CLI adapters.
