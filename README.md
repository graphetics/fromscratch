<img src="https://fromscratch.rocks/assets/img/icon.png">
# FromScratch

## A simple but smart note-taking app

FromScratch is a little app that you can use as a quick note taking or todo app.</p>

	* small and simple, the only UI is the text you type
	* saves on-the-fly, no need to manually save
	* automatic indenting
	* replaces common syntax with symbols, such as arrows

### Shortcuts

<ul>
	<li><kbd>cmd/ctrl+up</kbd> - move current line up</li>
	<li><kbd>cmd/ctrl+down</kbd> - move current line down</li>
	<li><kbd>cmd/ctrl+d</kbd> - delete current line</li>
	<li><kbd>cmd/ctrl+w/q</kbd> - close application</li>
	<li><kbd>cmd/ctrl+s</kbd> - ...this does nothing.</li>
</ul>

## Download
Recent downloads for OS X, Windows and Linux available on https://fromscratch.rocks

### Installation
```sh
# Download from git
git clone https://github.com/kilian/fromscratch.git

# Install dependencies
cd fromscratch && npm install

# build and run
npm build
electron main.js

# or run dev version
npm run hot-server

#in a different terminal:
npm run start-hot
```
### Credits

FromScratch is built upon these open source projects:
	<a href="http://electron.atom.io">Electron</a>,
	<a href="https://facebook.github.io/react/">React</a>,
	<a href="https://github.com/tonsky/FiraCode">Fira Code</a>,
	<a href="http://codemirror.net/">CodeMirror</a> and
	<a href="https://github.com/chentsulin/electron-react-boilerplate">Electron-react-boilerplate</a>.

Thanks to @bittersweet for helping me set up IPC to work around a particularly nasty bug, and @chentsulin for the electron-react-boilerplate.
