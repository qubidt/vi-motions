# More Vi Motions

Add more Vi Motions

## Motions added:


_Distributed with Zsh, enabled here:_

- Select quoted strings/tokens (`'`, `"`, or `` ` ``) as text objects
with `a` or `i` commands.
- Select bracketed strings/tokens (`( )`, `{ }`, `[ ]`, or `< >`) as text objects
with `a` or `i` commands.
- Change/delete surrounding quotes/brackets as in vim-surround.

_Distributed with this plugin, not enabled:_

- Change `W`, `B`, `E`, and `gE` motions to work on shell words
rather than blank words.
(See the end of `motions.zsh` for how to enable this.)

## Future additions(?):

*Select in/a command*

- surrounding backticks or `$( )`
- backwards to unescaped `;`, `{`, `(`, newline, or edge of buffer (call this `[;]`)
- or backwards to `[;]if`, `[;]elif`, `[;]else`, `[;]do`, `[;]while`, `[;]until`, `[;]repeat`, `[;]case`, `[;]then`
- forward to `[;]` or unescaped `}[;]`
- between `((` and `))`

*Select in/a command list*

- Between `[;]while`/`[;]until`/`[;]repeat` and `[;]do`/`{`/`(`
- Between `[;]select` and `[;]do`/`{`/`(`
- Between `[;]case` and `[;]esac`
- Between `[;]do` and `[;]done`
- Between `[;]if`/`[;]elif` and `[;]then`
- Between `[;]then` and `[;]elif`/`[;]fi`
- Between `[;]{` and `}[;]` or `[;](` and `)[;]`
