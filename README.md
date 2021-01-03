# tiddlywiki-muuri-kanban

## About

**tiddlywiki-muuri-kanban** is a Kanban plugin for [TiddlyWiki5](https://tiddlywiki.com) based on the [Muuri StoryView plugin](https://burningtreec.github.io/tiddlywiki-muuri) for TiddlyWiki5

## Installation

You can install the tiddlywiki-muuri-kanban plugin in two ways:

### NodeJs

clone this repo to your `TIDDLYWIKI_PLUGIN_PATH` (see https://tiddlywiki.com/#Environment%20Variables%20on%20Node.js)

```
git clone --depth=1 git@github.com:BurningTreeC/tiddlywiki-muuri-kanban.git $TIDDLYWIKI_PLUGIN_PATH
```

enable the plugin in your tiddlywiki.info file (see https://tiddlywiki.com/#tiddlywiki.info%20Files)

```
"plugins": [
	"plugins/first-plugin",
	"plugins/second-plugin",
	"tiddlywiki-muuri-kanban/BTC/Muuri-Kanban"
	]
```

### The TiddlyWiki SingleFile way

- go to https://burningtreec.github.io/tiddlywiki-muuri
- drag the link in the "Kanban Installation" tiddler to the Wiki where you want to install it
- don't forget to also install the [Muuri StoryView plugin](https://burningtreec.github.io/tiddlywiki-muuri#Installation)
- save your Wiki and reload