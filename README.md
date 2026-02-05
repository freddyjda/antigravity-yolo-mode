# Antigravity YOLO Mode

🏎️ **Auto-accept terminal commands in Antigravity**

![YOLO Mode Icon](icon.png)

## ⚠️ Important

**This extension ONLY auto-accepts terminal/console commands.** It does NOT automatically accept implementation plans - you still need to review those manually.

## What it does

- Runs `antigravity.agent.acceptAgentStep` every 2 seconds
- Auto-starts when Antigravity launches
- Toggle on/off with Command Palette → `YOLO: Toggle Auto-Accept`

## Installation

### From VSIX
1. Download the latest `.vsix` file
2. Open VS Code
3. Go to Extensions view (`Ctrl+Shift+X`)
4. Click the `...` menu → `Install from VSIX...`
5. Select the downloaded file

### From Marketplace
Search for "Antigravity YOLO Mode" in the VS Code Extensions Marketplace.

## Usage

### Toggle YOLO Mode
- Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
- Run: `YOLO: Toggle Auto-Accept`

### Status Bar
Check the bottom-right status bar:
- 🏎️ `YOLO: ON` - Auto-accepting enabled
- 🛑 `YOLO: OFF` - Auto-accepting disabled

## Requirements

- VS Code 1.80.0 or higher
- Antigravity extension installed

## Development

```bash
# Install dependencies
npm install

# Compile TypeScript
npm run compile

# Watch for changes
npm run watch

# Package extension
npx vsce package
```

## License

MIT
