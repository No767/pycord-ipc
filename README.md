# Pycord-IPC

A maintained inter-process-communication extension for Pycord

## Note

- The codebase is based off of [`pycord-ext-ipc`](https://github.com/xFGhoul/pycord-ext-ipc)
- Instead of using `aiohttp`, this library depends on `websockets` to communicate between the server and client. `aiohttp` is not a good ws server to begin with.
- Optional use of `uvloop` (only on MacOS and Linux)
- **This is not ready for production use, and is currently in the planning stages.**

## Installation

Python >= 3.8 is required.

```bash
pip install pycord-ipc
```