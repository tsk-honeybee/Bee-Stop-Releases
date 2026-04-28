# Bee Stop Releases

Public release channel for Bee Stop.

This repository intentionally does not contain the Bee Stop source code. It hosts:

- `latest.json` for plugin update checks
- public binary download files under `downloads/latest`

Update manifest URL:

```text
https://raw.githubusercontent.com/tsk-honeybee/Bee-Stop-Releases/main/latest.json
```

Stable download URLs:

```text
https://raw.githubusercontent.com/tsk-honeybee/Bee-Stop-Releases/main/downloads/latest/BeeStop-mac-vst3.zip
https://raw.githubusercontent.com/tsk-honeybee/Bee-Stop-Releases/main/downloads/latest/BeeStop-mac-au.zip
https://raw.githubusercontent.com/tsk-honeybee/Bee-Stop-Releases/main/downloads/latest/BeeStop-windows-vst3.zip
```

## Release Asset Names

Keep these names stable so the plugin can link to the latest build without needing a versioned filename:

- `BeeStop-mac-vst3.zip`
- `BeeStop-mac-au.zip`
- `BeeStop-windows-vst3.vst3`
- `BeeStop-windows-vst3.zip` if the Windows build outputs a VST3 bundle directory instead of a single `.vst3` file.

## Source Code

Bee Stop is distributed as binary freeware from this repository. The source code is not published here.
