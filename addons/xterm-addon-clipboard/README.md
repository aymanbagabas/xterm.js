## xterm-addon-clipboard

An addon for [xterm.js](https://github.com/xtermjs/xterm.js) that enables accessing the system clipboard. This addon requires xterm.js v4+.

### Install

```bash
npm install --save xterm-addon-clipboard
```

### Usage

```ts
import { Terminal } from 'xterm';
import { ClipboardAddon } from 'xterm-addon-clipboard';

const terminal = new Terminal();
const clipboardAddon = new ClipboardAddon();
terminal.loadAddon(clipboardAddon);
```

See the full [API](https://github.com/xtermjs/xterm.js/blob/master/addons/xterm-addon-clipboard/typings/xterm-addon-clipboard.d.ts) for more advanced usage.
