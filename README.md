<img src="assets/icon.svg" width="64" height="64" alt="">

# MM2

Created in [T3 Code](https://t3.codes).

Fork of Fleece's Mono MM2, patched to run in any game: the MM2-only
hard gate is removed and MM2 remotes load with timeouts, so universal
features (movement, ESP, utility) work everywhere while MM2-only
combat features sit inert outside MM2.

## Loadstring

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/streamversea22/mm2/refs/heads/master/src/Script.lua"))()
```

`src/Script.lua` is the base. `Loader.lua` holds the same one-liner
for copy-paste.
