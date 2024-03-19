Proof-of-concept: Loading Lua scripts for Kiddion's Modest Menu via Stand.

## Usage

Drop the `kiddions_compat.pluto` from this repository into your `%appdata%\Stand\Lua Scripts\lib` folder.

Add the following to the top of the script you're trying to load:

```lua
pluto_use * = false; require "kiddions_compat";
```

Now try loading the script via Stand.
