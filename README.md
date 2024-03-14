# cs2-cfg

My CS2 cfg.

## `autoexec.cfg`

You should place it at `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\autoexec.cfg`. Here is a one-liner to download it to there directly:

```console
curl.exe -L https://github.com/felipecrs/csgo-cfg/raw/master/autoexec.cfg --output 'C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\autoexec.cfg'
```

Or, if you have the repo cloned you can use symlinks:

```powershell
New-Item -ItemType SymbolicLink -Path "C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\autoexec.cfg" -Target "$(Resolve-Path ".\autoexec.cfg")" -Force
```

## Launch options

```
-novid -nojoy -high -windowed -noborder +exec autoexec
```
