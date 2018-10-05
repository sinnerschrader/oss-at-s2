# Talk | Open Source @ S2

How to work with this repository:

* create `.md` files in the `./src/` folder
* start `npm run watch` in the rot directory of the repository - the `.md` files in the source folder will be concatenated by a watcher and the result will be found in the `./dist/talk--opensource-at-S2.md` file
* open the `./dist/talk--opensource-at-S2.md` file in DeckSet (@decksetapp on Twitter)

Guidelines:

* separate the topics in separate files as good as possible
* "slides" are separated by `---`
* end each file with `\n---\n` (blank line, triple dash, blank line)
* The first `.md` file `00--*.md` contains the control information block for DeckSet. Be careful when editing.

To have a good experience while writing the talk I suggest the following:

* edit `.md` files in a tool like *VS Code*, *iA writer* or *Olysses*
* open the editor and DeckSet side-by-side
* do not edit the `talk--opensource-at-S2.md` file manually, *always* edit the separate chunk files
