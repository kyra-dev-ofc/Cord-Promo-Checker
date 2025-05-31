# Discord Promo Checker

A multi-threaded Discord promo code checker with proxy support.

## Features

- Reads proxies and promo codes from files.
- Uses proxies for HTTP requests.
- Concurrent checking using threads.
- Saves valid promos into categorized output files.

## Installation

1. Clone this repository or download the source code.

2. Install dependencies:

```bash
npm install chalk consola async-mutex undici enquirer
