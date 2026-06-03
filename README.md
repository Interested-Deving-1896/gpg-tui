[update-readmes]   Mode: rewrite — migrating to template structure...
# gpg-tui

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/gpg-tui)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/gpg-tui.git
cd gpg-tui
```

## Usage


```
gpg-tui [OPTIONS]
```

```
Options:
  -a, --armor                 Enables ASCII armored output
      --splash                Shows the splash screen on startup
      --config <path>         Sets the configuration file [env: GPG_TUI_CONFIG=]
      --homedir <dir>         Sets the GnuPG home directory [env: GNUPGHOME=]
  -o, --outdir <dir>          Sets the output directory [env: OUTDIR=]
      --outfile <path>        Sets the template for the output file name [env: OUTFILE=] [default: {type}_{query}.{ext}]
  -d, --default-key <key>     Sets the default key to sign with [env: DEFAULT_KEY=]
  -t, --tick-rate <ms>        Sets the tick rate of the terminal [env: TICK_RATE=] [default: 250]
  -c, --color <color>         Sets the accent color of the terminal [env: COLOR=] [default: gray]
  -s, --style <style>         Sets the style of the terminal [env: STYLE=] [default: colored] [possible values: plain, colored]
  -f, --file-explorer <app>   Sets the utility for file selection [env: FILE_EXPLORER=] [default: xplr]
      --detail-level <level>  Sets the detail level for the keys [env: DETAIL_LEVEL=] [default: minimum] [possible values: minimum, standard, full]
      --log-file <path>       Sets the file to save the logs [env: LOG_FILE=]
      --select <option>       Enables the selection mode [env: SELECT=] [possible values: row1, row2, key, key-id, key-fingerprint, user-id]
  -h, --help                  Print help (see more with '--help')
  -V, --version               Print version
```

## Configuration


It is possible to override the command line arguments with a configuration file.

See [gpg-tui.toml](config/gpg-tui.toml) for the default configuration values.

The configuration file can be specified via `--config` argument or `GPG_TUI_CONFIG` environment variable. Also, it can be placed to a location where **gpg-tui** looks for:

- `<config_dir>` `/` `gpg-tui.toml`
- `<config_dir>` `/` `gpg-tui/gpg-tui.toml`
- `<config_dir>` `/` `gpg-tui/config`

`<config_dir>` depends on the platform as shown in the following table:

| Platform | Value                                 | Example                                  |
| -------- | ------------------------------------- | ---------------------------------------- |
| Linux    | `$XDG_CONFIG_HOME` or `$HOME`/.config | /home/alice/.config                      |
| macOS    | `$HOME`/Library/Application Support   | /Users/Alice/Library/Application Support |
| Windows  | `{FOLDERID_RoamingAppData}`           | C:\Users\Alice\AppData\Roaming           |

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/gpg-tui`](https://github.com/Interested-Deving-1896/gpg-tui) and mirrored through:

```
Interested-Deving-1896/gpg-tui  ──►  OpenOS-Project-OSP/gpg-tui  ──►  OpenOS-Project-Ecosystem-OOC/gpg-tui
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/gpg-tui/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
