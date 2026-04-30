# noobhub Builds
This repository contains the pre-compiled binaries for noobhub.

## Binary Downloads
Binaries are organized by platform in their respective directories.

---

# noobhub TUI Controls

## Keyboard Shortcuts

### General Navigation

| Key | Action |
|-----|--------|
| `↑` / `↓` or `j` / `k` | Move up/down in lists |
| `enter` | Select / Action |
| `esc` | Go back |
| `q` or `ctrl+c` | Quit application |
| `ctrl+h` | Go to home |

### Search View

| Key | Action |
|-----|--------|
| `space` | Focus search bar |
| `ctrl+p` | Open player selection menu |
| `enter` | Play selected item |

### Episodes View

| Key | Action |
|-----|--------|
| `/` | Filter episodes |
| `tab` / `shift+tab` | Toggle content type (+/-) |

### Preview View

| Key | Action |
|-----|--------|
| `enter` or `p` | Play |

---

# Environment Variables

This application requires the following environment variables to be set:

| Variable | Description |
|----------|-------------|
| `TMDB_API_KEY` | API key for The Movie Database (TMDB) |
| `OPENSUBTITLES_USERNAME` | Username for OpenSubtitles |
| `OPENSUBTITLES_PASSWORD` | Password for OpenSubtitles |
| `OPENSUBTITLES_API_KEY` | API key for OpenSubtitles |

## Setting Environment Variables

Add these to your `.zshrc` or `.bashrc`:

```bash
export TMDB_API_KEY="your_tmdb_api_key"
export OPENSUBTITLES_USERNAME="your_username"
export OPENSUBTITLES_PASSWORD="your_password"
export OPENSUBTITLES_API_KEY="your_opensubtitles_api_key"
```

Then restart your shell or run `source ~/.zshrc`.