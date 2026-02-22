# InkyPi Joke of the Day Plugin

An [InkyPi](https://github.com/fatihak/InkyPi) plugin that displays a joke on your e-ink display, fetched from the JokeAPI with built-in fallback jokes for offline use.

## Screenshot

<!-- Add a screenshot of the plugin running on your display here -->

## Features

- Fetches a random joke from [JokeAPI](https://v2.jokeapi.dev) on each refresh
- Supports single-line jokes and two-part setup/punchline jokes
- Category filter: Any, Programming, Misc, Pun, Spooky, Christmas
- Safe mode to exclude explicit content
- Falls back to a built-in collection of jokes if the API is unavailable

## APIs Used

- **[JokeAPI v2](https://v2.jokeapi.dev)** — free, no API key required.
  - `GET /joke/{category}`

## Installation

Run the following command on your Raspberry Pi:

```bash
inkypi plugin install joke_of_day https://github.com/BloodAkatsuki/InkyPi-JokeOfDay
```

## Configuration

| Setting | Description |
|---|---|
| **Category** | Joke category: Any, Programming, Misc, Pun, Spooky, Christmas |
| **Safe Mode** | On: excludes explicit/dark content. Off: all jokes allowed |

## Status

Actively maintained.
