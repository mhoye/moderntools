# Modern Unix Tools

Modern problems require modern solutions.

This is a collection of very useful utilities that I've collected by asking the internet "What modern utilities should be a standard part of a modern unixy distro and why?" 

Additions and corrections via raised issue or pull requests are welcome.

# Utilities

## System use and management

*   [htop](https://htop.dev/), "a cross-platform interactive process viewer". 
*   [bottom](https://github.com/clementtsang/bottom), an htop-like utility that also got some votes.
*   [btop++](https://github.com/aristocratos/btop), another 'better top' variant.
*   [ncdu](https://dev.yorhel.nl/ncdu), friend of htop and a nice disk usage display for the terminal.
*   [HTTPie](https://httpie.io/), a CURL-adjacentish command-line HTTP client for testing and debugging web APIs.
*   [Xh](https://github.com/ducaale/xh) is related, described as reimplementing a subset of HTTPie's interface with an emphasis on simplicity and speed.
*   [glow](https://github.com/charmbracelet/glow), a markdown-on-the-command-line tool. 
*   [Lowdown](https://github.com/kristapsdz/lowdown), also a markdown tool, also interesting.
*   [fzf](https://github.com/junegunn/fzf) and [skim](https://github.com/lotabout/skim) are both interesting CLI "fuzzy finders" (but take a look at 'z' further down this list.)
*   [tldr](https://tldr.sh/) - simplified man pages with practical examples. The world has needed this for a long time.
*   [Tree](https://linuxhandbook.com/tree-command/): show you the tree structure of directories, a bit like microdosing on Midnight Commander from back in the day.
*   [Broot](https://github.com/Canop/broot): better navigation of directory trees.
*   [atool](https://linux.die.net/man/1/atool), a set of scripts that wrap common compressed-file-format handlers.
*   [LazyDocker](https://github.com/jesseduffield/lazydocker) and [LazyGit](https://github.com/jesseduffield/lazygit), CLI improvements for Docker and Git respectively.
*   [hwatch](https://github.com/blacknon/hwatch) and [viddy](https://github.com/sachaos/viddy), two alternatives to the venerable and underappreciated "watch" command.

## Data management

A collection of modern data migration, conversion and management tools.

*   [Gron](https://github.com/tomnomnom/gron), a tool for making JSON greppable.
*   [jq](https://stedolan.github.io/jq/) and [jid](https://github.com/simeji/jid) are both fantastic tools for inspecting and manipulating JSON.
*   [ijq](https://sr.ht/~gpanders/ijq/), an "interactive jq".
*   [xidel](https://github.com/benibela/xidel): this looks like jq-for-html, and I'm intrigued.
*   [csvkit](https://github.com/wireservice/csvkit): if you spend a lot of time working with comma-separated values, accept no substitutes.
*   [miller](https://github.com/johnkerl/miller), a CSV multitool.
*   [VisiData](https://www.visidata.org/): a tabular data visualization multitool.
*   [duc](https://duc.zevv.nl/), also a nice drive-use visualizer.
*   [matplotlib](https://matplotlib.org/): the upgrade over gnuplot you've been waiting for.
*   [st](https://github.com/nferraz/st), "Simple Statistics", a command-line app that calculates the sum, mean, standard deviation, and a few other things about a set of numbers.
*   [Datamash](https://www.gnu.org/software/datamash/): Gnu, I know, but an interesting command-line-math tool.
*   [Dasel](https://github.com/TomWright/dasel), short for Data Selector, like jq/yq but with more supported data formats.
*   [nushell](https://www.nushell.sh/): A structured-data pipeline-building _shell_.
*   [rclone](https://rclone.org/), a cloud-storage data-moving multitool, similar to rsync.
*   [unison](https://github.com/bcpierce00/unison): a file synchronizer, can keep two directories in sync bi-directionally.

## Specialized tools

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
*   [lsd](https://github.com/Peltoche/lsd) and [eza](https://github.com/eza-community/eza), new takes on the venerable ls. (Note: this previously referred to exa, rather than eza, but exa has apparently been forked and abandoned.
*   [zoxide](https://github.com/ajeetdsouza/zoxide): an interesting update to, of all things, cd!
*   [z](https://github.com/rupa/z): another "better cd", but a very cool frecency-and-regex-matching "faster/smarter cd".
*   [ag](https://github.com/ggreer/the_silver_searcher): the Silver Searcher, a better ack (which was in turn born "a better grep").
*   [just](https://github.com/casey/just): Just, a modernization of the venerable Make.
*   [Meli email](https://meliemail.org/): An extensible terminal based mail client; a work in progress, but an elegant improvement on Mutt.
*   [Aerc](https://aerc-mail.org/): Another email client for the terminal, described as highly efficient and extensible, perfect for the discerning hacker.

## Shells, shell customizations and ergonomic improvements

*   [fish](https://fishshell.com): Finally, a command line shell for the 90s. Non-posix, but with nice defaults for interactive use right out of the box (very little need for custom configuration and plugins).
    * [OhMyFish](https://github.com/oh-my-fish/oh-my-fish): Plugin system for fish, for those missing complexity.
    * [Fisher](https://github.com/jorgebucaran/fisher): The other plugin manager for fish, compatible with oh-my-fish plugins.
*   [zsh](https://en.wikipedia.org/wiki/Z_shell): A modernized, modular update to Bash with a lot of new utility built in, as well as its [remarkable collection of plugins](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins)
    * [OhMyZsh](https://github.com/ohmyzsh/ohmyzsh/) + [Alacritty](https://github.com/alacritty/alacritty): this trifecta of terminal emulator, shell and shell extensions turns out to be a powerful combination.
*   [Starship.rs](https://starship.rs/): Cross-shell prompt customization that looks very pretty.
*   [atuin](https://github.com/atuinsh/atuin): "magical shell history", storing shell history in an SQLite DB and offering fully-encrypted shell-history sync between devices.
*   [mcfly](https://github.com/cantino/mcfly): replaces the usual ctrl-r shell-history search handler with a more powerful tool, super cool.
*   [tmux](https://github.com/tmux/tmux/wiki), a terminal multiplexer.
*   Some people mentioned [screen](https://www.gnu.org/software/screen/manual/screen.html), the classic tool in this space, but noted that it's getting pretty long in the tooth and tmux is a pure improvement.

## Quality-Of-Life command line improvements.

*   [the "ducks" alias.](https://gist.github.com/thebouv/8657674)
*   The author's own [per-project shell history hack](https://gist.github.com/mhoye/469ed97d7887b451da5d45b87acb53f5)

## Other collections

*   The [moreutils](https://joeyh.name/code/moreutils/) collection.
*   [Terminal Trove](https://terminaltrove.com/), the "$HOME of all things in the terminal".
  
