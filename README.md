# HTTP Live Simulator

`http-live-simulator` is a simple http file server for local development written in Node.JS. It is similar, for instance, to python's `http.server` module or PHP's built-in server (`php -S <end-point>`), but with one major difference: It adds a random time delay of 200-500 milliseconds for each requested resource in order to simulate a live environment where such delays are a common occurrence.

## Installation:

`npm install -g http-live-simulator`

## Usage:

```
$ http-live
Serving Directory: /your/current/path
Port 8080
Delay: 200-500ms
```

You can change the behaviour of http live server with following optional arguments:

```
Optional arguments:
  -h, --help            Show this help message and exit.
  -v, --version         Show program's version number and exit.
  -p PORT, --port PORT  Port number for running the server
  -m MIN_DELAY, --min-delay MIN_DELAY
                        Minimum Delay
  -x MAX_DELAY, --max-delay MAX_DELAY
                        Maximum Delay
```

## Uninstallation:

`npm uninstall -g http-live-simulator`
