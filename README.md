# Modern Unix Tools

Modern problems require modern solutions.

This is a collection of very useful utilities that I've collected by asking the internet "What modern utilities should be a standard part of a modern unixy distro and why?" 

Additions and corrections via raised issue or pull requests are welcome.

# Utilities

## System use and management

*   [htop](https://htop.dev/), "a cross-platform interactive process viewer". 
*   An [htop-like utility called bottom](https://github.com/clementtsang/bottom) also got some votes.
*   [tmux](https://github.com/tmux/tmux/wiki), a terminal multiplexer.
*   Some people mentioned [screen](https://www.gnu.org/software/screen/manual/screen.html), the classic tool in this space, but noted that it's getting pretty long in the tooth and tmux is a pure improvement.
*   [HTTPie](https://httpie.io/), a CURL-adjacentish command-line HTTP client for testing and debugging web APIs.
    *   [Xh](https://github.com/ducaale/xh) is related, described as reimplementing a subset of HTTPie's interface with an emphasis on simplicity and speed.
*   [glow](https://github.com/charmbracelet/glow), a markdown-on-the-command-line tool. 
*   [Lowdown](https://github.com/kristapsdz/lowdown), also a markdown tool, also interesting.
*   [fzf](https://github.com/junegunn/fzf), a command-line "fuzzy finder".
*   [tldr](https://tldr.sh/) - simplified man pages with practical examples. The world has needed this for a long time.
*   [zsh](https://en.wikipedia.org/wiki/Z_shell): A modernized, modular update to Bash with a lot of new utility built in.
** [OhMyZsh](https://github.com/ohmyzsh/ohmyzsh/) + [Alacritty](https://github.com/alacritty/alacritty): this trifecta of terminal emulator, shell and shell extensions turns out to be a powerful combination.
*   [Tree](https://linuxhandbook.com/tree-command/): show you the tree structure of directories, a bit like microdosing on Midnight Commander from back in the day.
*   [Broot](https://github.com/Canop/broot): better navigation of directory trees.
*   [atool](https://linux.die.net/man/1/atool), a set of scripts that wrap common compressed-file-format handlers.
*   [mcfly](https://github.com/cantino/mcfly): replaces the usual ctrl-r shell-history search handler with a more powerful tool, super cool.
*   [ncdu](https://dev.yorhel.nl/ncdu), friend of htop and a nice disk usage display for the terminal.
*   [LazyDocker](https://github.com/jesseduffield/lazydocker) and [LazyGit](https://github.com/jesseduffield/lazygit), CLI improvements for Docker and Git respectively.

## Data management

A collection of modern data migration, conversion and management tools.

*   [Gron](https://github.com/tomnomnom/gron), a tool for making JSON greppable.
*   [VisiData](https://www.visidata.org/): a tabular data visualization multitool.
*   [jq](https://stedolan.github.io/jq/) and [jid](https://github.com/simeji/jid) are both fantastic tools for inspecting and manipulating JSON.
*   [duc](https://duc.zevv.nl/), also a nice drive-use visualizer.
*   [rclone](https://rclone.org/), a cloud-storage data-moving multitool.
*   [csvkit](https://github.com/wireservice/csvkit): if you spend a lot of time working with comma-separated values, accept no substitutes.
*   [matplotlib](https://matplotlib.org/): the upgrade over gnuplot you've been waiting for.
*   [xidel](https://github.com/benibela/xidel): this looks like jq-for-html, and I'm intrigued.
*   [nushell](https://www.nushell.sh/): A structured-data pipeline-building _shell_.
*   [miller](https://github.com/johnkerl/miller), a CSV multitool.
*   [st](https://github.com/nferraz/st), "Simple Statistics", a command-line app that calculates the sum, mean, standard deviation,  and a few other things about a set of numbers.
*   [ijq](https://sr.ht/~gpanders/ijq/), an "interactive jq".
*   [Datamash](https://www.gnu.org/software/datamash/): Gnu, I know, but an interesting command-line-math tool.

## Specialized Tools

"Do one thing and do it well."

*   [LatexDiff](https://github.com/ftilmann/latexdiff/): Like it says on the tin, Diff for Latex.
*   [dyff](https://github.com/homeport/dyff): diff for yaml.

## Revisiting The Classics

A collection of tools best described as "A better $X"

*   [ply](https://wkz.github.io/ply/), described as "bpftrace without the drama."
*   [duf](https://github.com/muesli/duf) a better df.
*   [ripgrep](https://github.com/BurntSushi/ripgrep), a line-oriented search tool, described as a better grep.
*   [sd](https://github.com/chmln/sd), a better sed.
*   [fd](https://crates.io/crates/fd-find), a better find
*   [bat](https://github.com/sharkdp/bat), a better cat.
*   [dust](https://github.com/bootandy/dust), a better du.
*   [lsd](https://github.com/Peltoche/lsd) and [exa](https://the.exa.website/), new takes on the venerable ls.
*   There's also [zoxide](https://github.com/ajeetdsouza/zoxide): an interesting update to, of all things, cd!
*   [ag](https://github.com/ggreer/the_silver_searcher): the Silver Searcher, a better ack (which was in turn born "a better grep").
*   [just](https://github.com/casey/just): Just, a modernization of the venerable Make.
*   [Meli email](https://meliemail.org/): An extensible terminal based mail client; a work in progress, but an elegant improvement on Mutt.
*   [z](https://github.com/rupa/z): another "better cd", but a very cool frecency-and-regex-matching "faster/smarter cd".
*   [atuin](https://github.com/atuinsh/atuin): "magical shell history", storing shell history in an SQLite DB and offering fully-encrypted shell-history sync between devices.

## Quality-Of-Life command line improvements.

*   [the "ducks" alias.](https://gist.github.com/thebouv/8657674)
*   Re-upping [OhMyZsh](https://github.com/ohmyzsh/ohmyzsh/) here for its [remarkable collection of plugins](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins)

## Other collections

*   The [moreutils](https://joeyh.name/code/moreutils/) collection.
