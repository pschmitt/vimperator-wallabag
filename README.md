# vimperator-wallabag

There may be no API [yet](https://github.com/wallabag/wallabag/issues/414) but here's the corresponding Vimperator plugin.

## Installation

```bash
[[ -z $VIMPERATOR_RUNTIME ]] && VIMPERATOR_RUNTIME=~/.vimperator
git clone https://github.com/pschmitt/vimperator-wallabag.git "${VIMPERATOR_RUNTIME}/plugin/vimperator-wallabag"
```

## Configuration

Add `let g:wallabag_url="http://YOUR_URL"` to your `vimperatorrc`.

## Usage

`:w[allaba]g [URL]`

If `URL` isn't set, the current URL will be used.
