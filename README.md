# Angelical Scripts

A self-hosted script repository for Roblox Lua scripts.

## Features

- 📝 Upload and host Lua scripts
- 🔗 Direct script URLs for script executors
- 💾 Scripts stored in browser localStorage
- 🎨 Dark theme with syntax highlighting
- ⚡ Fast and lightweight

## Usage

### Uploading Scripts

1. Go to https://angelical-me.github.io
2. Enter script name (e.g., `anti-logger.lua`)
3. Paste your Lua code
4. Click "Upload Script"

### Getting Script URLs

Each script gets a direct URL:

```
https://angelical-me.github.io/scripts/anti-logger.lua
https://angelical-me.github.io/scripts/your-script.lua
```

### Using with Script Executors

With executors like Synapse X, Roblox Studio, etc., use:

```lua
loadstring(game:HttpGet("https://angelical-me.github.io/scripts/anti-logger.lua"))()
```

## Limitations

- Scripts are stored in browser localStorage
- Only persist on the device used to upload
- Data is lost if browser cache is cleared

## Security Note

⚠️ **Never share sensitive credentials in scripts!** Hosted scripts are accessible to anyone with the URL.

---

Enjoy hosting your Roblox scripts! 🚀