# Bee Stop Releases

Public release channel for Bee Stop.

This repository intentionally does not contain the Bee Stop source code. It hosts:

- `latest.json` for plugin update checks
- GitHub Release assets such as `BeeStop-mac-vst3.tar.gz`
- release notes and third-party notices

Update manifest URL:

```text
https://raw.githubusercontent.com/tsk-honeybee/Bee-Stop-Releases/main/latest.json
```

Stable download URLs:

```text
https://github.com/tsk-honeybee/Bee-Stop-Releases/releases/latest/download/BeeStop-mac-vst3.tar.gz
https://github.com/tsk-honeybee/Bee-Stop-Releases/releases/latest/download/BeeStop-mac-au.tar.gz
https://github.com/tsk-honeybee/Bee-Stop-Releases/releases/latest/download/BeeStop-windows-vst3.vst3
```

## Release Asset Names

Keep these names stable so the plugin can link to the latest build without needing a versioned filename:

- `BeeStop-mac-vst3.tar.gz`
- `BeeStop-mac-au.tar.gz`
- `BeeStop-windows-vst3.vst3`
- `BeeStop-windows-vst3.tar.gz` if the Windows build outputs a VST3 bundle directory instead of a single `.vst3` file.

## Source Code

Bee Stop is distributed as binary freeware from this repository. The source code is not published here.
