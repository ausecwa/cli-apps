# Awesome list of CLI/TUI programs

This repository contains a list of (mainly) CLI/TUI apps with links and a short description.
To the best of my knowledge, this is the largest collection of CLI/TUI tools available in the form of awesome list.

The peculiarity of this repository is that the source of information is structured into CSV files with a simple structure.
See the `data/` directory.

This `README` file is generated from the CSV files.
To build `README.md` run:

```
make
```

`python3` is required for building. And `make`, of course. :-)

# How to contribute

If you have any suggestion or want your project included in the list, you can either open a pull request or send me an email with the necessary information.

If you want to contribute through a pull request, make sure to add new entries to the correct CSV file under the `data/` directory.
Please commit the CSV file only, not the README.
I will review the request and, upon acceptance, I will take care of generating the README and updating the list.

If you prefer an email, contact me at `toolleeo@gmail.com`.

# Summary

To date, **599** apps/tools covered, divided in **43** categories.

# Index

[Backup](#backup) (8) | [Calculators](#calc) (4) | [Chat and instant messaging](#chat) (8) | [Conversion](#conversion) (6) | [Data management](#data-management) (25) | [Data transfer](#transfer) (28) | [Directory changers](#cd) (8) | [Disk usage analyzers](#disk-analyzer) (8) | [Editors](#editors) (20) | [Email](#email) (9) | [File and file system handling](#file-handling) (32) | [File manager](#file-manager) (9) | [File renamers](#file-renamer) (6) | [File systems](#file-system) (3) | [Font management](#font) (2) | [Funny tools](#funny) (15) | [Games](#games) (29) | [Git and accessories](#git) (20) | [Graphics](#graphics) (14) | [Multimedia](#multimedia) (3) | [Networking](#networking) (15) | [Note taking](#note-taking) (12) | [Office tools](#office) (14) | [Organizers and calendars](#organizers) (12) | [Online search and resources](#online) (7) | [Password managers](#password-manager) (10) | [Productivity](#productivity) (18) | [Programming](#programming) (19) | [Science](#science) (8) | [Security and encryption](#security) (9) | [Shells](#shells) (5) | [Sound and music](#music) (24) | [System monitoring](#monitor) (26) | [System tools](#system) (19) | [Terminals](#terminal) (9) | [Text processing](#text-processing) (32) | [Text search](#text-search) (9) | [Todo managers](#todo-manager) (14) | [Utilities](#utility) (22) | [Versioning](#versioning) (5) | [Viewers](#viewers) (24) | [Web browser](#browser) (16) | [Web development](#webdev) (13)

Some links to [related resources](#resources).

## <a name="backup"></a>Backup

* [borg](https://github.com/borgbackup) - Encrypted backups with a clean and simple interface; easy to use and set up; possibility to mount the backup archive with FUSE and inspect it as a regular file system.  
* [bupstash](https://github.com/andrewchambers/bupstash) - Easy and efficient encrypted backups.
* [duplicity](http://duplicity.nongnu.org/) - Creates GPG encrypted, compressed backups; client-side encryption allows to upload the backup onto untrusted servers.
* [Duply](http://duply.net/) - Simplifies the use of [duplicity](http://duplicity.nongnu.org/) by keeping clean configuration files to automate the backup.  
* [paperbackup](https://github.com/intra2net/paperbackup) - Create a pdf with barcodes to backup text files on paper.
* [shallow-backup](https://github.com/alichtman/shallow-backup) - Git integrated backup tool.
* [Zaloha.sh](https://github.com/Fitus/Zaloha.sh) - Shellscript for synchronization of files and directories.
* [zbackup](http://zbackup.org/) - A globally-deduplicating backup tool, based on the ideas found in rsync.

## <a name="calc"></a>Calculators

* [bcal](https://github.com/jarun/bcal) - Byte CALculator - A REPL CLI utility for storage expression evaluation, SI/IEC conversion, byte address calculation, base conversion and LBA/CHS calculation.
* [kalk](https://github.com/PaddiM8/kalk) - Command line calculator that supports math-like syntax with user-defined variables, functions, derivation, integration, and complex numbers.
* [Nota](https://kary.us/nota/) - Terminal calculator with rich notation.
* [Qalculate](https://qalculate.github.io/) - Multi-purpose calculator with customizable functions, units, arbitrary precision, plotting (it includes a GUI).

## <a name="chat"></a>Chat and instant messaging

* [finch](http://www.pidgin.im/) - IM program supporting many protocols, including Yahoo!, AIM, IRC, or WLM; comes with the `Pidgin` project.
* [irssi](http://www.irssi.org) - The most popular IRC client for the command-line; a flexible program, with many options and supporting many protocols.
* [matterhorn](https://github.com/matterhorn-chat/matterhorn) - A terminal client for the Mattermost chat system.
* [RainbowStream](http://www.rainbowstream.org/) - Twitter client for the terminal; allows almost all the operations that can be done from GUI and Web clients.
* [ssh-chat](https://github.com/shazow/ssh-chat) - Custom SSH server written in Go. Instead of a shell, you get a chat prompt.
* [tiny](https://github.com/osa1/tiny) - tiny is an IRC client written in Rust.
* [tuir](https://gitlab.com/ajak/tuir) - Reddit TUI
* [WeeChat](http://weechat.org/) - A "fast, light and extensible chat client".

## <a name="conversion"></a>Conversion

* [BaFi](https://mmalcek.github.io/bafi/) - Universal JSON, BSON, YAML, CSV, XML translator to ANY format using templates.
* [catdoc](http://www.wagner.pp.ru/~vitus/software/catdoc/) - Command line converter from Microsoft Word to plain text; output is sent to the standard output.  
* [mdBook](https://github.com/rust-lang/mdBook) - Create book from markdown files.
* [Pandoc](http://pandoc.org/) - Universal document file converter; handles input output from/to a number of formats: HTML, PDF, LaTeX, docx, odt, AsciiDoc, Markdown, Textile, just to mention a few; the quality of conversion strongly depends on the combination of input/output formats.
* [simtex](https://github.com/iaacornus/simtex) - simtex (simplified LaTeX) allows you to convert your markdown or text lectures into LaTeX file with one command, configured with simple .json file.
* [xls2csv](http://www.wagner.pp.ru/~vitus/software/catdoc/) - Command line converter from Excel to CSV file format.  

## <a name="data-management"></a>Data management

* [csvkit](https://github.com/wireservice/csvkit) - A suite of command-line tools for converting to and working with CSV, the king of tabular file formats.
* [csvq](https://github.com/mithrandie/csvq) - SQL-like query language for csv.
* [dasel](https://github.com/TomWright/dasel) - Allows you to query and modify data structures using selector strings.
* [datadash](https://github.com/keithknott26/datadash) - Visualize and graph data in the terminal.
* [Dolt](https://github.com/dolthub/dolt) - Dolt is Git for Data! Dolt is a SQL database that you can fork, clone, branch, merge, push and pull just like a git repository.
* [GNU Recutils](https://www.gnu.org/software/recutils/manual/) - Set of tools and libraries to access human-editable, text-based databases called recfiles.
* [gnuplot](https://www.explainshell.com/explain/1/gnuplot) - Generate two and three dimensional plots of data.
* [gojq](https://github.com/itchyny/gojq) - Pure Go implementation of jq.
* [Graphtage](https://github.com/trailofbits/graphtage) - Graphtage is a commandline utility and underlying library for semantically comparing and merging tree-like structures, such as JSON, XML, HTML, YAML, plist, and CSS files.
* [IRedis](https://github.com/laixintao/iredis) - Interactive Redis: A Cli for Redis with AutoCompletion and Syntax Highlighting.
* [jq](https://github.com/stedolan/jq) - (JSON Query?) is sed-like processor for JSON data; can be used to process JSON files and data streams and perform operations such as those allowed by `cat`, `sed`, `grep` and `awk` on regular text files.
* [jtc](https://github.com/ldn-softdev/jtc) - JSON manipulation and transformation.
* [lowcharts](https://github.com/juan-leon/lowcharts) - lowcharts is meant to be used in those scenarios where we have numerical data in text files that we want to display in the terminal to do a basic analysis.
* [mycli](https://github.com/dbcli/mycli) - A command line client for MySQL that can do auto-completion and syntax highlighting.
* [osmf](https://github.com/codesoap/osmf) - OpenStreetMap find - A simple command line tool to explore OSM data.
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
* [q](http://harelba.github.io/q/) - Executes SQL-like queries on CSVs/TSVs tabular data files; each tabular file is treated as a database table; support to all SQL constructs (`WHERE`, `GROUP BY`, `JOIN`).
* [sq](https://github.com/neilotoole/sq) - Command line tool that provides jq-style access to structured data sources such as SQL databases, or document formats like CSV or Excel.
* [TSV Utilities](https://github.com/eBay/tsv-utils) - Command line tools for large, tabular data files.
* [usql](https://github.com/xo/usql) - Universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, and others, including NoSQL and non-relational databases.
* [VisiData](https://www.visidata.org/) - Interactive multitool for tabular data. It combines the clarity of a spreadsheet, the efficiency of the terminal, and the power of Python, into a lightweight utility which can handle millions of rows with ease.
* [WOPR](https://github.com/yaronn/wopr) - A simple markup language for creating rich terminal reports, presentations and infographic.
* [xsv](https://www.johndcook.com/blog/2019/12/31/sql-join-csv-files/) - Doing a SQL join with CSV files.
* [yq](https://github.com/mikefarah/yq) - Portable command-line YAML processor.
* [zq](https://zed.brimdata.io/docs/commands/zq/) - Processor for JSON data with stateful operators and a syntax that is more consistent w.r.t. jq (as claimed by the authors).

## <a name="transfer"></a>Data transfer

* [aria2](https://github.com/aria2/aria2) - Lightweight and easy-to-use download utility; it supports HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink and multiple sources; cross-platform.
* [croc](https://github.com/schollz/croc) - Easily and securely send things from one computer to another.
* [curl](https://curl.haxx.se/) - A tool and library for transferring data with URL syntax; supports a lot of protocols.  
* [Deluge](http://deluge-torrent.org/) - A lightweight, Free Software, cross-platform BitTorrent client; a terminal curses interface, web interface and command line client can connect to a running daemon to manage torrent downloads.
* [Jitter](https://github.com/sharpcdf/jitter) - A repository-oriented binary manager for Linux, Jitter searches through online repository (currently only on GitHub) for releases with .tar.gz, .tgz, .zip or .AppImage assets.
* [lftp](https://lftp.yar.ru/) - "Sophisticated ftp/http client, and a file transfer program supporting a number of network protocols"; support for bookmarks and mirroring features.
* [Mabel](https://github.com/smmr-software/mabel) - Deriving its name from the Hebrew word "מבול," meaning flood, deluge, or (loosely) torrent, Mabel is a fancy BitTorrent client for the terminal.
* [Magic Wormhole](https://github.com/warner/magic-wormhole) - The program allows transfer arbitrary-sized files and directories (or short pieces of text) from one computer to another The two endpoints are identified by using identical human-readable codes.  
* [OnionShare](https://onionshare.org/) - "An open source tool that lets you securely and anonymously share a file of any size." 
* [portal](https://github.com/SpatiumPortae/portal) - A quick and easy command-line file transfer utility from any computer to another.
* [qr-filetransfer](https://github.com/sdushantha/qr-filetransfer) - Transfer files over WiFi between your computer and your smartphone from the terminal.
* [qrcp](https://www.linuxuprising.com/2020/07/qrcp-transfer-files-between-desktop-and.html) - Transfer Files Between Desktop And Mobile Devices Over Wi-Fi By Scanning A QR Code.
* [rclone](https://rclone.org/) - Rclone manages file synchronization on cloud storage.
* [rsync](https://download.samba.org/pub/rsync/rsync.html) - Mirror directories across networked machines; handles diffs/changed files; works across SSH; plenty of parameters.  
* [rtorrent](https://github.com/rakshasa/rtorrent) - Bittorrent client uses ncurses and is ideal for use with tmux, screen or dtach.
* [sitecopy](http://www.manyfish.co.uk/sitecopy/) - Synchronizes a local copy of a website with a remote copy on a server; does not use SSH/`scp` but FTP for file copy; useful when the remote server does not support secure copy.  
* [stftp](http://stftp.sourceforge.net/) - (simple terminal FTP) aims to be a "easy-to-use and unbloated client for the UNIX (and UNIX-like) console".
* [Stig](https://github.com/rndusr/stig) - Stig is a client application to connect and control the BitTorrent Transmission client app.
* [torrentCLI](https://github.com/amogusussy/torrentCLI) - Get torrents from the Terminal.
* [Transgression TUI](https://github.com/PanAeon/transg-tui) - A remote TUI client for the Transmission bittorrent program.
* [Transmission](https://transmissionbt.com/) - Fast, easy and free bittorrent client.
* [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - File synchronizer. It allows two replicas of a collection of files and directories to be stored on different hosts (or different disks on the same host), modified separately, and then brought up to date by propagating the changes in each replica to the other.
* [Woof](http://www.home.unix-ag.org/simon/woof.html) - (Web Offer One File) sets up an HTTP webserver to serve files from a given local directory; all the users connected to the network can see and download the files.  
* [xh](https://github.com/ducaale/xh) - xh is a friendly and fast tool for sending HTTP requests. It reimplements as much as possible of HTTPie's excellent design.
* [youtube-dl](http://rg3.github.io/youtube-dl/) - Downloads videos from [YouTube](https://www.youtube.com/) and some other sites; useful for automated bulk downloads.  
* [yt-splitter](https://github.com/redsolver/yt-splitter) - Downloads and splits audio tracks from a YouTube video according to the chapters/tracks. Useful for compilations or full album uploads.
* [ytfzf](https://github.com/pystardust/ytfzf) - A POSIX script that helps you find Youtube videos (without API) and opens/downloads them using mpv/youtube-dl.
* [ytmdl](https://github.com/deepjyoti30/ytmdl) - Get songs from Youtube in mp3 format.

## <a name="cd"></a>Directory changers

* [broot](https://dystroy.org/broot/) - A new way to navigate directory trees on linux, made in rust.
* [fasd](https://github.com/clvv/fasd) - A Commandline Tool That Offers Quick Access to Files and Directories. It offers quick access to files and directories for POSIX shells.  It is inspired by tools like autojump, z and v. Fasd keeps track of files and directories you have accessed, so that you can quickly reference them in the command line.
* [fastdiract](https://github.com/dp12/fastdiract) - Lightning-fast cd and command execution.
* [Jmp](https://github.com/gholmes829/Jmp) - Change directory with smart searching of the path specified through regex.
* [llama](https://github.com/antonmedv/llama) - Minimalistic file opener and directory changer focused on fuzzy searching the path.
* [pazi](https://github.com/euank/pazi) - Fast autojump helper.
* [SmartCd](https://github.com/CodesOfRishi/smartcd) - A cd command with improved usability features, which can remember your recently visited directory paths and, search and directly traverse to sub-directories and as well as parent directories, all with Fuzzy searching.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem.

## <a name="disk-analyzer"></a>Disk usage analyzers

* [diskus](https://github.com/sharkdp/diskus) - Minimal, fast alternative to du -sh.
* [dua](https://github.com/Byron/dua-cli) - Disk Usage Analyzer. Learn about the usage of disk space of a given directory with parallel access to max out SSD exploration.
* [duf](https://github.com/muesli/duf) - Disk Usage/Free Utility.
* [Dust](https://github.com/bootandy/dust) - du + rust = dust. Like du but more intuitive.
* [dutree](https://github.com/nachoparker/dutree) - A tool to analyze file system usage written in Rust.
* [gdu](https://github.com/dundee/gdu) - Pretty fast disk usage analyzer written in Go. Gdu is intended primarily for SSD disks where it can fully utilize parallel processing. However HDDs work as well, but the performance gain is not so huge.
* [ncdu](https://dev.yorhel.nl/ncdu) - "A disk usage analyzer with an ncurses interface.  It is designed to find space hogs on a remote server where you don't have an entire graphical setup available."
* [vizex](https://github.com/bexxmodd/vizex) - Visualize the disk space usage for every partition and media on the user's machine.

## <a name="editors"></a>Editors

* [ash](https://github.com/akashnag/ash) - A simple and clean terminal-based text editor, that aims to be easy to use with modern key-bindings.
* [Diakonos](https://github.com/Pistos/diakonos) - A powerful editor with “standard” keybindings and several advanced features; written in Ruby.
* [Emacs](https://www.gnu.org/software/emacs/) - One of the godfathers of text editors; free long-standing software project; tons of extensions and funcionalities; the biggest drawback (my taste): it needs [E-Lisp](https://www.gnu.org/software/emacs/manual/eintr.html) for being programmed.  
* [eon](https://github.com/tomas/eon) - A light, modern editor for your terminal that doesn't want to be vim.
* [Helix](https://github.com/helix-editor/helix) - A kakoune / neovim inspired editor, written in Rust. The editing model is very heavily based on kakoune.
* [jed](http://www.jedsoft.org/jed/index.html) - A text editor with a drop-down menu facility that make it especially user-friendly.  
* [joe](http://joe-editor.sourceforge.net/) - (Joe's Own Editor) is a compact text editor written in C; a detailed list of features and missing ones is explicitly reported in the website; this editor is mentioned in several web sources for its capability in handling large files.  
* [Kakoune](http://kakoune.org/) - Modal editor, faster as in less keystrokes, multiple selections, orthogonal design.
* [micro](https://github.com/zyedidia/micro/) - A terminal-based text editor written in Go that aims to be easy to use and intuitive, while also taking advantage of the full capabilities of modern terminals.
* [nano](https://www.nano-editor.org/) - Easy to use, lightweigth text editor; no complex keybindings to remember.
* [neovim](https://github.com/neovim/neovim) - A work in progress attempt to improve [vim](http://www.vim.org/), dropping older/unused OS compatibility, improving the codebase readability, modularity and maintainability; it has chances to become the next choice of vim users.
* [o](https://github.com/xyproto/o) - Configuration-free text editor and IDE limited to VT100. Suitable for writing git commit messages, editing Markdown, config files, source code, viewing man pages and for quick edit-compile cycles when programming.
* [slap](https://github.com/slap-editor/slap) - Text editor inspired by [Sublime Text](https://www.sublimetext.com/) written in NodeJS; extedable in Javascript.  
* [Tilde](https://os.ghalkes.nl/tilde/) - Tilde is a text editor that provides an intuitive interface for people accustomed to GUI environments, usual shortcuts for common operation, a traditional menu bar, etc.
* [vai](https://github.com/stefanoborini/vai) - A text editor similar to `vim` written in Python; many feature are nicely replicated, some are still missing; however, the advantage of this implementation is its simplicity, maintainability and extensibility, thanks to the Python implementation.
* [vim](http://www.vim.org/) - Historically one of the preferred text editors; behavior based on editing modes; plenty of plugins and tips to address every possible editing problem.  
* [vis](https://github.com/martanne/vis) - "a modern, legacy free, simple yet efficient vim-like editor", and more: "The intention is not to be bug for bug compatible with vim, instead a similar editing experience should be provided. The goal could thus be summarized as 80% of vim's features implemented in roughly 1% of the code"; the editor is scriptable in LUA and supports editing large files.
* [vy](https://github.com/vyapp/vy) - A vim-like in python made from scratch.
* [WordGrinder](https://cowlark.com/wordgrinder/) - From the website: "WordGrinder is a word processor for processing words. It is not WYSIWYG. It is not point and click. It is not a desktop publisher. It is not a text editor. It does not do fonts and it barely does styles. What it does do is words. It's designed for writing text. It gets out of your way and lets you type." 
* [zee](https://github.com/zee-editor/zee) - Zee is a modern editor for the terminal, in the spirit of Emacs. It is written in Rust and it is somewhat experimental.

## <a name="email"></a>Email

* [alot](https://github.com/pazz/alot) - MUA written in Python using the [NotMuch](https://notmuchmail.org/) backend; MailDir format support.  
* [alpine](http://www.washington.edu/alpine/) - Mail client which aims at being "fast, easy to use email client that is suitable for both the inexperienced email user as well as for the most demanding of power users".
* [mbsync](http://isync.sourceforge.net/mbsync.html) - Mailboxes synchronization tool; allows to download email locally; MailDir format supported.  
* [Mutt](http://www.mutt.org/) - Mail client with tons of features, customization chances, support for IMAP, POP3, multiple storage formats.
* [NeoMutt](https://neomutt.org/) - Patched and up-to-dated mutt fork.
* [Newsbeuter](http://newsbeuter.org/) - "The Mutt of RSS Feed Readers": Newsbeuter is an open-source RSS/Atom feed reader for text terminals. Has great configurability and vast number of features, making it a slick and fast feed reader that can be completely controlled via keyboard.
* [nmail](https://github.com/d99kris/nmail) - nmail is a console-based email client for Linux and macOS with a user interface similar to alpine / pine.
* [pymailgen](https://github.com/toolleeo/pymailgen) - Starting from the content of a CSV file and a template text file, pymailgen generates a list of emails to be sent out using a command-line SMTP client.
* [sup](https://github.com/sup-heliotrope/sup) - MUA written in Ruby; specifically developed for accounts with "a lot of emails"; nice thread-based presentation.

## <a name="file-handling"></a>File and file system handling

* [alder](https://github.com/aweary/alder) - Directory tree visualizer.
* [Brash](https://github.com/zakariagatter/brash) - CLI Trash Manager in Pure Bash.
* [classifier](https://github.com/bhrigu123/classifier) - Organize files in your current directory, by classifying them into folders of music, pdfs, images, etc.
* [cv](https://github.com/Xfennec/progress) - (Coreutils Progress Viewer) "looks for coreutils basic commands (`cp`, `mv`, `dd`, `tar`, `gzip/gunzip`, `cat`, etc.) currently running on your system and displays the percentage of copied data. It can also show estimated time and throughput".
* [detox](http://detox.sourceforge.net/) - A utility designed to easily clean up filenames; it replaces characters like spaces with standard equivalents; it also replace UTF-8 or Latin-1 (or CP 1252) characters with more handy ones.  
* [doppelganger](https://github.com/witchard/doppelganger) - Save and load your shell environment to create doppelganger shells!
* [dtrx](https://brettcsmith.org/2007/dtrx/) - (Do The Right eXtraction) aims at taking "all the hassle out of extracting archives"; allows to use one command to extract archives in different formats, recursive extraction (files into file) and extracts files into dedicated directories.
* [exa](https://the.exa.website/) - Replacement for 'ls' written in Rust, with colors and several additional "views".
* [FClones](https://github.com/pkolaczk/fclones) - Efficient Duplicate File Finder.
* [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find. Written in Rust.
* [ff](https://github.com/akymos/ff) - ff is a command-line tool to manage favorite folders, creating an alias, to be used via shell directly with the cd command.
* [file-type-cli](https://github.com/sindresorhus/file-type-cli) - Detect the file type of a file or stdin.
* [friendly-find](https://github.com/sjl/friendly-find) - Usable replacement for find.
* [gcp](https://github.com/petronny/gcp) - `gcp` (Goffi’s cp) is an advanced file copier tool, heavily inspired from the traditional `cp` command utility, but with some additional features: Displays the copy progress indicator, with estimated time, current file speed; logs of all actions; resume of interrupted copy processes.
* [ictree](https://github.com/NikitaIvanovV/ictree) - Like tree but interactive.
* [inventory](https://github.com/mothdotmonster/inventory) - Move files like an old text adventure.
* [ll](https://github.com/antonmedv/ll) - ls with git status.
* [nat](https://github.com/willdoescode/nat) - Complete replacement for the `ls` command.
* [PathPicker](https://facebook.github.io/PathPicker/) - A tool from Facebook that parses the output from a command and presents a UI to select files and directories; can be used to apply a command of a interactively selected files or to move across directories.  
* [progress](https://github.com/Xfennec/progress) - A tool to monitor the progress of common Coreutils command-line tools (`cp`, `mv`, `dd`, `tar`, `rsync`, etc.); it uses an ncurses interface to display the percentage of data copied; it works by reading from system files and retrieving the necessary information for the estimation.
* [pycp](https://github.com/dmerejkowsky/pycp) - cp and mv with a progressbar.
* [RecoverPy](https://github.com/PabloLec/RecoverPy) - RecoverPy is a powerful tool that leverages your system capabilities to recover lost files. Unlike others, you can not only recover deleted files but also overwritten data.
* [rip](https://github.com/nivekuil/rip) - Safe and ergonomic alternative to rm.
* [rmlint](https://github.com/sahib/rmlint/) - A tool to recursively scan a directory tree looking for duplicate and broken files; it outputs statistics and save the list of files in JSON format; it produce a shell script that can be inspected before running it to delete the desire files.  
* [trash-cli](https://github.com/sindresorhus/trash-cli) - Move files and folders to the trash.
* [tree](http://mama.indstate.edu/users/ice/tree/) - "Recursive directory listing command that produces a depth indented listing of files".
* [twf](https://github.com/wvanlint/twf) - Standalone tree view file explorer.
* [vidir](https://github.com/trapd00r/vidir) - vidir allows editing of the contents of a directory in a text editor.
* [watchexec](https://github.com/watchexec/watchexec) - Executes commands in response to file modifications.
* [wfh](https://github.com/kzys/wfh) - Continuously watches your local directories and rsync them against a remote host.
* [xcp](https://github.com/tarka/xcp) - Extended cp.
* [xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer, stealing ideas from nnn and fzf.

## <a name="file-manager"></a>File manager

* [clifm](https://github.com/leo-arch/clifm) - A CLI-based, shell-like, and non-curses terminal file manager written in C: simple, fast, extensible, and lightweight as hell.
* [hunter](https://github.com/rabite0/hunter) - Ranger-like file browser written in rust.
* [lfm](https://inigo.katxi.org/devel/lfm/) - (Last File Manager) is a file manager written in Python; it comes with lots of features, including 1-pane or 2-pane view, files filters and bookmarks, tree view, virtual file-systems to open compressed archives, search in files, customizable keybindings and themes.
* [Midnight Commander](http://www.midnight-commander.org/) - a visual file manager, full-screen text mode application that allows you to copy, move and delete files and whole directory trees and search for files; includes an internal viewer and editor.
* [ncursesFM](https://github.com/FedeDP/ncursesFM) - File manager written in C; rather complete in terms of features; especially lightweight and responsive.  
* [nnn](https://github.com/jarun/nnn) - "The missing terminal file browser for X". Provides only directory traversal and file visualization.  No delete/move operations are supported.
* [ranger](https://ranger.github.io/) - Console file manager with vi key bindings; curses interface with a view on the directory hierarchy; comes with a file launcher that automatically determines which program to use for opening a given file type.  
* [rnr](https://github.com/bugnano/rnr) - The RNR File Manager (RNR's Not Ranger) is a text based file manager that combines the best features of Midnight Commander and Ranger.
* [vifm](https://vifm.info/) - "ncurses based file manager with vi like keybindings/modes/options/commands/configuration, which also borrows some useful ideas from mutt" (cit.).

## <a name="file-renamer"></a>File renamers

* [F2](https://github.com/ayoisaiah/f2) - Cross-platform command-line tool for batch renaming files and directories quickly and safely.
* [massren](https://github.com/laurent22/massren) - Easily rename multiple files using your text editor.
* [mmv](https://github.com/itchyny/mmv) - Rename multiple files using your $EDITOR. The command name is named after multi-mv.
* [nomino](https://github.com/yaa110/nomino) - Batch rename utility for developers.
* [rename](https://www.kernel.org/pub/linux/utils/util-linux/) - Included in `util-linux`, allows bulk rename of files with regex support.
* [renameutils](http://www.nongnu.org/renameutils/) - A set of programs to change file and directory names by editing them inplace; I find `imv` especially useful to edit a filename at the program prompt.  

## <a name="file-system"></a>File systems

* [sshfs](https://github.com/libfuse/sshfs) - Locally mount a remote file-system through SSH and access files and directory as they would be on the local machine.  
* [TMSU](http://tmsu.org/) - A tool for tagging files; it provides a simple command line tool for applying tags and a virtual filesystem so that you can get a tag-based view of your files from within any other program.  
* [wutag](https://github.com/wojciechkepka/wutag) - CLI Tool for tagging and organizing files by tags.

## <a name="font"></a>Font management

* [FIGlet](http://www.figlet.org/) - Not exactly a font manager, but a nice program for making large letters out of ordinary text; an astonishing number of different fonts is available.
* [toilet](http://caca.zoy.org/wiki/toilet) - A program that tries to improve `FIGlet`; can load FIGlet fonts; supports Unicode input and output, colour fonts and output, and various output formats, including HTML, IRC and ANSI; uses `libcaca` to produce nice textual effects.

## <a name="funny"></a>Funny tools

* [asciiacquarium](http://www.robobunny.com/projects/asciiquarium/html/) - Enjoy the mysteries of the sea from the safety of your own terminal!
* [cbonsai](https://gitlab.com/jallbrit/cbonsai) - A bonsai tree generator, written in C using ncurses. It intelligently creates, colors, and positions a bonsai tree.
* [cli-fireplace](https://github.com/dolsup/cli-fireplace) - Shows digital fireplace.
* [cmatrix](http://www.asty.org/cmatrix/) - ncurses program that display the scrolling lines found in the movie `The matrix`.
* [cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) - A program that generates a ASCII art of a cow with a bubble containing the specified message (I provide the Wikipedia link since at the moment the link to the author's homepage results to be unreachable).  
* [cowthink](https://en.wikipedia.org/wiki/Cowsay) - Same as `cowsay`, but uses a "think" bubble instead of a speech bubble.
* [Draw](https://github.com/maaslalani/draw) - draw is an simple drawing tool in the terminal. Hold your mouse down and move it across the screen to draw anything you want!
* [fortune](http://software.clapper.org/fortune/) - Generates random messages feched from a quotation database.  
* [Limoji](https://github.com/GEROGIANNIS/Limoji) - Limoji is an open source tool that makes it easy to choose between hundreds of cool ASCII emoticons and share them with your friends.
* [pokeget](https://github.com/talwat/pokeget) - A bash script you can use to display cool sprites of pokemon in your terminal.
* [ponysay](https://github.com/erkin/ponysay) - Pony rewrite of cowsay.
* [sha256-animation](https://github.com/in3rsha/sha256-animation) - Animation of the SHA-256 hash function in your terminal.
* [Steam Locomotive](http://www.cyberciti.biz/tips/displays-animations-when-accidentally-you-type-sl-instead-of-ls.html) - A steam locomotive traverses the screen from right to left if `sl` is typed instead of `ls`.  
* [ternimal](https://github.com/p-e-w/ternimal) - Simulate a lifeform in the terminal.
* [yosay](https://github.com/yeoman/yosay) - Like cowsay, but for yeoman.

## <a name="games"></a>Games

* [Angband](https://rephial.org/) - Angband is a free, single-player dungeon exploration game.
* [bastet](http://fph.altervista.org/prog/bastet.html) - (Bastard Tetris) implements the classical Tetris but with a logic to generate the next block which maximizes the difficulty for the player.  
* [Cataclysm: Dark Days Ahead](https://cataclysmdda.org/) - Open source turn-based survival RPG development project.
* [chs](https://github.com/nickzuber/chs) - Play chess against the Stockfish engine in your terminal.
* [clidle](https://github.com/ajeetdsouza/clidle) - Wordle, now over SSH.
* [crappybird-py](https://github.com/JonPizza/crappybird-py) - Flappy bird.
* [Dwarf fortress](http://www.bay12games.com/dwarves/) - A fantasy game using ASCII art graphical representation of the game environment; it features a rich environment with many options and possibilities.  
* [freesweep](http://www.upl.cs.wisc.edu/~hartmann/sweep/) - A Minesweeper clone for the terminal which allows you to configure settings such as table rows and columns up to 1024x1024!), percentage of bombs, colors and also has a highscores table.
* [gambit](https://github.com/maaslalani/gambit) - Chess board in your terminal.
* [GameShell](https://github.com/phyver/GameShell) - GameShell was devised as a tool to help university students to engage with a real shell, in a way that encourages learning while also having fun.
* [Language-games](https://github.com/Hellisotherpeople/Language-games) - Dead simple games made with word vectors.
* [minesweeper](https://github.com/gazpachoking/minesweeper) - Cross-platform terminal based minesweeper.
* [Minesweeper Game](https://github.com/omerkarabacak/minesweeper) - A small command line Minesweeper Game.
* [Nethack](http://nethack.org/) - Single player rogue-like dungeon exploration game.
* [Oldrunner](http://culot.org/public/Code/oldrunner.html) - Character-based remake of Lode Runner; includes all the original 150 levels.  
* [othello-cli](https://github.com/LelsersLasers/othello-cli) - othello-cli is a cli version of Othello (Reversi) written in Rust. You can play against another player, the AI, or watch two AIs play each other.
* [Pokete](https://github.com/lxgr-linux/pokete) - A terminal based Pokemon like game.
* [rpg-cli](https://github.com/facundoolano/rpg-cli) - Your filesystem as a dungeon!
* [sku](https://github.com/fedeztk/sku) - Simple TUI written in go to play sudoku in the terminal.
* [Slash'EM](http://slashem.sourceforge.net/) - Rogue-like game derived from `nethack` offering extra features, monsters, and items; includes a GUI version.
* [sssnake](https://github.com/AngelJumbo/sssnake) - (Smart and sexy snake) The classic snake game for the terminal that can plays itself and be use like a screensaver.
* StarWars vision - See Star Wars in ASCII with ``telnet towel.blinkenlights.nl``.  
* [terdle](https://github.com/neelkarma/terdle) - Wordle implemented in Rust.
* [Terminal Phase](https://dustycloud.org/blog/terminal-phase-1.0/) - A space shooter game you can play in your terminal.
* [terminal_board_games](https://github.com/salt-die/terminally_bored_terminal_board_games) - Board games for the terminal.
* [terminordle](https://github.com/HP4k1h5/terminordle) - Inspired by the popular online game wordle made, you can play a pretty close replica of the original locally or multiplayer over the network.
* [Typespeed](http://typespeed.sourceforge.net/) - Type words that are flying by from left to right as fast as you can; features different word sets, e.g., UNIX commands, English words, Non-English words.
* [usolitaire](https://github.com/eliasdorneles/usolitaire) - Solitaire in your terminal.
* [wordle-curses](https://github.com/knosmos/wordle-curses) - A simple TUI wordle game with curses.

## <a name="git"></a>Git and accessories

* [czg](https://github.com/Zhengqbbb/cz-git) - Interactively generate standardized commit messages.
* [forgit](https://github.com/wfxr/forgit) - A utility tool powered by fzf for using git interactively.
* [fzf-git.sh](https://github.com/junegunn/fzf-git.sh) - bash and zsh key bindings for Git objects, powered by fzf.
* [gh-f](https://github.com/gennaro-tedesco/gh-f) - The ultimate, compact and snappy fzf extension for gh cli.
* [gh-s](https://github.com/gennaro-tedesco/gh-s) - Search github repositories interactively.
* [gh-stars](https://github.com/aymanbagabas/gh-stars) - A GitHub CLI extension to show repository stargazers.
* [git](https://git-scm.com/) - The winner across all the existing file versioning tools; distributed versioning; fully controllable from the command-line; plenty of configuration and usage options; behind a number of related project that leverage git as backend.  
* [git-annex](https://git-annex.branchable.com/) - Manages files with `git`, without checking the file contents into git; very useful to manage large/binary files.
* [git-extras](https://github.com/tj/git-extras) - Little git extras like git-ignore, git-setup, git-changelog, git-release, git-effort and more.
* [git-peek](https://github.com/Jarred-Sumner/git-peek) - git peek is the fastest way to open a remote git repository in your local text editor.
* [git-remote-aws](https://github.com/nathants/git-remote-aws) - Management of encrypted git hosting.
* [git-stats](https://github.com/IonicaBizau/git-stats) - Local git statistics including GitHub-like contributions calendars.
* [Gitea](https://gitea.com/) - Single binary self-hosted Git service.
* [gitui](https://github.com/extrawurst/gitui) - GitUI provides you with the comfort of a git GUI but right in your terminal
* [grv](https://github.com/rgburke/grv) - Git Repository Viewer - A terminal based interface for viewing Git repositories. It allows refs, commits and diffs to be viewed, searched and filtered.
* [onefetch](https://github.com/o2sh/onefetch) - Git repository summary on your terminal.
* [sad](https://github.com/ms-jpq/sad) - CLI search and replace. Show you a nice diff of proposed changes before you commit them.
* [Soft Serve](https://github.com/charmbracelet/soft-serve) - Self-hostable Git server for the command line. One distinguished feature is the possibility to create new repositories with a push.
* [stargazer](https://github.com/gennaro-tedesco/stargazer) - Github stats from the command line.
* [tig](https://github.com/jonas/tig) - An ncurses-based text-mode interface for `git` that can act as a repository browser, but can also assist in staging changes for commit at chunk level.

## <a name="graphics"></a>Graphics

* [Artem](https://github.com/FineFindus/artem) - Convert images from multiple formats (jpg, png, webp, etc…) to ASCII art, written in Rust.
* [chafa](https://github.com/hpjansson/chafa) - Terminal graphics for the 21st century.
* [cli-mandelbrot](https://github.com/danyshaanan/cli-mandelbrot) - A cli for traversing the Mandelbrot fractal.
* [givegif](https://github.com/passy/givegif) - GIFs on the command line.
* [GraphicsMagick](http://www.graphicsmagick.org/) - Swiss army knife of image processing.
* [ImageMagick](http://www.imagemagick.org/script/index.php) - Software suite to create, edit, compose, or convert bitmap images; it handles many file formats (including PDF and SVG) and provides processing tools to "resize, flip, mirror, rotate, distort, shear and transform images, adjust image colors, apply various special effects, or draw text, lines, polygons, ellipses and Bézier curves".
* [imgcat](https://github.com/trashhalo/imgcat) - Tool to output images in the terminal. Built with bubbletea.
* [imgp](https://github.com/jarun/imgp) - A command line image resizer and rotator for JPEG and PNG images. It can resize (or thumbnail) and rotate thousands of images in a go, at lightning speed, while saving significantly on storage.
* [inklayers](https://github.com/toolleeo/inklayers) - A command line program that exports layers from an SVG file. It can be used to create slide shows by editing a single SVG file.
* [jp2a](https://csl.name/jp2a/) - Command-line tool that converts images to ASCII art in the Linux terminal.
* [kakikun](https://github.com/file-acomplaint/kakikun) - Kakikun is a tool to paint, draw and create ASCII art in your terminal using unicode characters.
* [pastel](https://github.com/sharkdp/pastel) - A command-line tool to generate, analyze, convert and manipulate colors.
* [scrot](https://github.com/dreamer/scrot) - A simple CLI tool to capture screenshots.  
* [svgcleaner](https://github.com/RazrFalcon/svgcleaner) - Clean up your SVG files from the unnecessary data.

## <a name="multimedia"></a>Multimedia

* [Editly](https://github.com/mifi/editly) - A tool and framework for declarative NLE (non-linear video editing) using Node.js and ffmpeg.
* [ffmpeg](https://ffmpeg.org/) - The Swiss knife of video editing from the command line.
* [invidtui](https://github.com/darkhz/invidtui) - Invidious client, which fetches data from invidious instances and displays a user interface in the terminal(TUI), and allows for selecting and playing Youtube audio and video.

## <a name="networking"></a>Networking

* [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
* [bluetuith](https://github.com/darkhz/bluetuith) - A TUI-based Bluetooth connection manager, which can interact with Bluetooth adapters and devices. It aims to be a replacement to most Bluetooth managers, like blueman.
* [bore](https://github.com/ekzhang/bore) - A simple CLI tool for making tunnels to localhost.
* [geoiplookup](https://github.com/maxmind/geoip-api-c) - a little application to find geographical and network information of an IP address based no the geoip C API.
* [ipcalc](http://jodies.de/ipcalc) - "ipcalc takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range." 
* [mitmproxy](https://mitmproxy.org/) - An interactive HTTPS proxy.
* [PSSH](https://code.google.com/archive/p/parallel-ssh/) - PSSH provides parallel versions of OpenSSH and related tools. Included are pssh, pscp, prsync, pnuke, and pslurp. The project includes psshlib which can be used within custom applications.
* [quickserve](https://github.com/charliesome/quickserve) - Quickserve is a very simple HTTP server written in Python that is intended for quickly sharing files on an ad-hoc basis. Aside from opening a port in your firewall if you have one, quickserve requires no set-up and should work with no hassle.
* [redive](https://github.com/neelkarma/redive) - Trace URL redirections in the terminal.
* [rtop](http://www.rtop-monitor.org/) - rtop is a simple, agent-less, remote server monitoring tool that works over plain SSH. Written in golang, it does not need any software to be installed on the server that you want to monitor. It works by establishing an SSH session, and running commands on the remote server to collect system metrics.
* [Rustcat](https://github.com/robiot/rustcat) - Netcat Alternative in Rust.
* [speedtest-net](https://github.com/ddsol/speedtest.net) - Test internet connection speed and ping using speedtest.net.
* [termishare](https://github.com/qnkhuat/termishare) - Peer to peer terminal sharing.
* [TStream](https://github.com/qnkhuat/tstream) - Live streaming from the terminal. Requires the connection to a central server, from which the streaming is dispatched.
* [xxh](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the ssh.

## <a name="note-taking"></a>Note taking

* [cadmus](https://github.com/RyanGreenup/cadmus) - Shell Scripts to Facilitate Effective Note Taking.
* [dn](https://github.com/tomlockwood/dn) - Daily notes command line tool.
* [dnote](https://github.com/dnote/dnote) - A simple command line notebook for the terminal. It also offers a seamless multi-device sync and a web interface.
* [eureka](https://github.com/simeg/eureka) - Store your ideas without leaving the terminal.
* [Geeknote](https://github.com/jeffkowalski/geeknote) - A command line client for Evernote that can be use on Linux, FreeBSD and OS X.
* [jnrl](https://github.com/maebert/jrnl) - Collect your thoughts and notes without leaving the command line.
* [kb](https://github.com/gnebbia/kb) - A minimalist knowledge base manager.
* [nb](https://github.com/xwmx/nb) - A command line and local web note‑taking, bookmarking, archiving, and knowledge base application.
* [posce](https://github.com/posce/posce) - A note-taking toolkit for your command line.
* [sncli](https://github.com/insanum/sncli) - A Python application that gives you access to your Simplenote account via the command line.
* [Standard Unix Notes](https://github.com/Standard-Unix-Notes/unix-notes) - GPG Encrypted Notes/Notebook manager for BSD/Linux.
* [Terminal velocity](https://vhp.github.io/terminal_velocity/) - A fast, cross-platform note-taking application for the UNIX terminal.

## <a name="office"></a>Office tools

* [conan](https://github.com/mirage/conan) - Find clue about the type of the file.
* [conrad](https://github.com/vinayak-mehta/conrad) - Track conferences and meetups.
* [Lotus 1-2-3 for Linux](https://github.com/taviso/123elf#lotus-1-2-3-for-linux) - A native port of Lotus 1-2-3 Release 3 to Linux.
* [mdp](https://github.com/visit1985/mdp) - A command-line based markdown presentation tool.
* [Quoter](https://github.com/frossm/quoter) - The console based stock quote tool.
* [sc-im](https://github.com/andmarti1424/sc-im) - Spreadsheet Calculator Improvised -- An ncurses spreadsheet program for terminal. It is rich in functionalities, but the syntax of functions and other details are different from the common spreadsheets such as Excel and Calc, making difficult to "re-cycle" existing knowledge on these programs to work proficiently with sc-im. Neverthless, a nice piece of software."
* [scholarref](https://adamsgaard.dk/scholarref.html) - Tools to never deal with journal webpages again.
* [sent](https://tools.suckless.org/sent/) - Simple plaintext presentation tool.
* [Teapot](https://www.syntax-k.de/projekte/teapot/) - Compact ncurses-based spreadsheet with original syntax, 3D-style and built-in functions.
* [Ticker](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker.
* [tpp](http://www.ngolde.de/tpp.html) - (text presentation program) a ncurses Ruby program that allows to produce nice text-based presentation with simple markup language.
* [translate-shell](https://github.com/soimort/translate-shell) - Command-line translator using Google Translate or other online services.
* [trino](https://github.com/eneserdogan/trino) - Quick and easy translation of words and phrases entered in the command line.  
* [wikit](https://github.com/KorySchneider/wikit) - A command line program for getting Wikipedia summaries easily.

## <a name="organizers"></a>Organizers and calendars

* [addrb](https://github.com/mrusme/addrb) - A lightweight CLI / TUI address book that supports CardDAV.
* [buku](https://github.com/jarun/buku) - A powerful bookmark manager written in Python3 and SQLite3.
* [calcurse](https://calcurse.org/) - A calendar and scheduling application for the command line. It helps keep track of events, appointments and everyday tasks.
* [gcalcli](https://github.com/insanum/gcalcli) - CLI to access Google Calendars; allows to do the main tasks: create, delete, and list events.
* [goobook](https://gitlab.com/goobook/goobook) - The purpose of GooBook is to make it possible to use your Google Contacts from the command-line and from MUAs such as Mutt.  It can be used from Mutt the same way as abook.
* [khal](https://github.com/pimutils/khal) - CLI and terminal calendar program, able to synchronize with CalDAV servers through [vdirsyncer](https://github.com/pimutils/vdirsyncer).
* [khard](https://github.com/lucc/khard) - Console carddav client written in Pyhton.  
* [Org mode](http://orgmode.org/) - Super-powerful [Emacs](https://www.gnu.org/software/emacs/) plugin to manage outlines with associated timestamps, priorities, labels, etc.; available views grouped by time (agenda), tags, etc.; plain text storage format.
* [pal](http://palcal.sourceforge.net/) - Calendar program for Unix/Linux systems that can keep track of events; custom, plain text storage format; interesting and fully functional.
* [ppl addressbook](http://ppladdressbook.org/) - ``ppl`` is free software made out of other free software.  It's built on top of Ruby and Git, and the completely free vcard address book format.
* [Remind](https://www.roaringpenguin.com/products/remind) - Calendar program with possibility to set complex rules to define events; custom, powerful text-based storage format.
* [Wyrd](http://freecode.com/projects/wyrd/) - Curses front-end for [Remind](https://www.roaringpenguin.com/products/remind) written in OCaml with vertically scrollable time table.  

## <a name="online"></a>Online search and resources

* [arch-wiki](https://github.com/deadhead420/arch-wiki) - Search the Arch Wiki anywhere from the command line.  
* [Awesome CLI](https://github.com/umutphp/awesome-cli) - Awesome CLI is a simple command line tool to give you a fancy command line interface to dive into Awesome lists.
* [ddgr](https://github.com/jarun/ddgr) - A command line utility to search DuckDuckGo (html version) from the terminal.
* [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal.
* [so](https://github.com/samtay/so) - Terminal interface for Stack Overflow.
* [socialscan](https://github.com/iojw/socialscan) - Python library and CLI for accurately querying username and email usage on online platforms.
* [socli](https://github.com/gautamkrishnar/socli) - Stack overflow command line client written in Python.  Search and browse stack overflow without leaving the terminal 

## <a name="password-manager"></a>Password managers

* [Bitwarden CLI](https://bitwarden.com/help/cli/) - Command-line interface for Bitwarden, a multi-platform password manager targeted to companies and enterprises.
* [cpass](https://github.com/OliverLew/cpass) - Another console UI for pass.
* [dpg](https://github.com/62726164/dpg) - The Deterministic Password Generator - Generates passwords based on a master password and the indication of the website/service/username, without the need of storing anything.
* [gopass](https://www.gopass.pw/) - gopass is a rewrite of the pass password manager in Go with the aim of making it cross-platform and adding additional features. The target audience are professional developers and sysadmins (and especially teams of those) who are well versed with a command line interface.
* [hide](https://github.com/whatl3y/hide) - AES-256 bit encrypted password manager with all encrypted passwords stored locally on your machine
* [kpcli](http://kpcli.sourceforge.net/) - A command line interface for KeePass.
* [pass](https://www.passwordstore.org/) - With pass, each password lives inside of a gpg encrypted file whose filename is the title of the website or resource that requires the password. These encrypted files may be organized into meaningful folder hierarchies, copied from computer to computer, and, in general, manipulated using standard command line file management utilities.
* [safe.sh](https://github.com/windowsrefund/safe) - Pure Bash script to manage secure archives; simple and clean; uses [gnugpg](https://gnupg.org/) for encryption/decryption, thus can leverage tools like [GPG Agent](https://www.gnupg.org/documentation/manuals/gnupg/Invoking-GPG_002dAGENT.html).
* [SpicyPass](https://github.com/JFreegman/SpicyPass) - A light-weight password manager with a focus on simplicity and security.
* [titan](https://www.byteptr.com/titan/) - Password management belongs to the command line, deep into the Unix heartland, the shell. Titan is written in C and is available under the MIT license.

## <a name="productivity"></a>Productivity

* [ancv](https://github.com/alexpovel/ancv) - Renders your (JSON) resume/CV for online & pretty terminal display.
* [arbtt](http://arbtt.nomeata.de/) - (automatic, rule-based time tracker) runs in background, collecting information regarding open windows, focussed ones, etc.; it can be configured to display statistics on the collected data, e.g., figuring out the time spent on one specific window.
* [Bartib](https://github.com/nikolassv/bartib) - Easy to use time tracking tool for the command line. It saves a log of all tracked activities as a plaintext file and allows you to create flexible reports.
* [cowyo](https://github.com/schollz/cowyo) - Feature rich wiki webserver for minimalists.
* [dijo](https://github.com/NerdyPepper/dijo) - Scriptable, curses-based, digital habit tracker.
* [fasttyper](https://github.com/ickyicky/fasttyper) - Fasttyper is minimalistic typing test based on user provided exercising text.
* [gdir](https://github.com/pafoster/gdir) - A command line tool which queries Google Directions. The tool displays results as human-readable text.
* [h-m-m](https://github.com/nadrad/h-m-m) - h-m-m (pronounced like the interjection "hmm") is a simple, fast, keyboard-centric terminal-based tool for working with mind maps.
* [habitctl](https://github.com/blinry/habitctl) - Minimalist command line tool you can use to track and examine your habits.
* [hledger](https://hledger.org/) - A is fast, reliable, free, multicurrency double-entry accounting software to track money, investments, cryptocurrencies, time, or any other quantifiable commodity; uses a future-proof plain text file format.
* [ledger](http://ledger-cli.org/) - A powerful, double-entry accounting system from the command-line; it uses a simple yet powerful text syntax to specify the items to account.
* [paycon](https://github.com/arcorion/paycon) - Converts pay amounts between different time units.
* [Taskell](https://github.com/smallhadroncollider/taskell) - A CLI kanban board/task manager for Mac and Linux.
* [thokr](https://github.com/thatvegandev/thokr) - Sleek typing tui with visualized results and historical logging.
* [toipe](https://github.com/Samyak2/toipe) - Yet another typing test, but crab flavoured.
* [Translate Shell](https://www.soimort.org/translate-shell/) - Command-line translator using Google Translate, Bing Translator, Yandex.Translate, etc.
* [tuxi](https://github.com/Bugswriter/tuxi) - A CLI tool that scrapes Google search results and SERPs that provides instant and concise answers.
* [Watson](https://github.com/TailorDev/Watson) - Time tracking CLI to know how much time you are spending on your projects. It can generate nice reports for clients.

## <a name="programming"></a>Programming

* [chars](https://github.com/antifuchs/chars) - Display names and codes for various ASCII (and unicode) characters / code points.
* [cloc](https://github.com/AlDanial/cloc) - Tool for counting blank lines, comment lines, and physical lines of source code in many programming languages.
* [Cppcheck](http://cppcheck.net/) - Static analysis tool for C/C++ code providing unique code analysis to detect bugs and focuses on detecting undefined behaviour and dangerous coding constructs.
* [dtool](https://github.com/guoxbin/dtool) - Collection of development tools.
* [Frama-C](https://frama-c.com/) - Open-source extensible and collaborative platform dedicated to source-code analysis of C software. Frama-C can assist from the navigation through unfamiliar projects up to the certification of critical software.
* [gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard) - Modular visual interface for GDB in Python.
* [grex](https://github.com/pemistahl/grex) - A command-line tool for generating regular expressions from user-provided test cases.
* [hors](https://github.com/WindSoilder/hors) - Instant coding answers via the command line.
* [kickstart](https://github.com/Keats/kickstart) - Scaffolding tool to get new projects up and running quickly.
* [license-up](https://github.com/nikitavoloboev/license-up) - Create a license quickly for a given name.
* [nbterm](https://github.com/davidbrochart/nbterm) - Jupyter Notebooks in the terminal.
* [pire](https://github.com/johannestaas/pire) - Python Interactive Regular Expressions.
* [Proji](https://github.com/nikoksr/proji) - Powerful cross-platform CLI project templating tool.
* [pvcheck](https://github.com/claudio-unipv/pvcheck) - A tool to apply automated testing to programs that produce textual output. The format of the output is very specific, making pvcheck suitable to test programming quizzes.
* [rr](https://rr-project.org/) - Debug the recording, deterministically, as many times as you want.
* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code (scc) is a codebase statistics counter. Goal is to be the fastest code counter possible, but also perform COCOMO calculation like sloccount and to estimate code complexity similar to cyclomatic complexity calculators. In short one tool to rule them all.
* [scons](https://github.com/SCons/scons) - Software construction tool.
* [temci](https://github.com/parttimenerd/temci) - Advanced benchmarking tool written in Python 3 that supports setting up an environment for benchmarking and the generation of visually appealing reports.
* [Tokei](https://github.com/XAMPPRocky/tokei) - Tokei is a program that displays statistics about your code. Tokei will show the number of files, total lines within those files and code, comments, and blanks grouped by language.

## <a name="science"></a>Science

* [bib.awk](https://github.com/huijunchen9260/bib.awk) - Bibliography manager written in awk.
* [cobib](https://gitlab.com/mrossinek/cobib) - Simple, command-line based bibliography management tool.
* [element](https://github.com/gennaro-tedesco/element) - Periodic table on the command line.
* [FAWOC](https://github.com/robolab-pavia/fawoc) - FAWOC is a TUI program for manually labelling a list of words. It has been developed to support the efficient clustering of documents based on topic modeling algorithms such as Dirichlet Latent Allocation.
* [papis](https://github.com/alejandrogallo/papis) - Extensible document and bibliography manager.
* [pt.sh](https://github.com/alexeytal/pt.sh) - CLI periodic table with search and many properties.
* [Pubs](https://github.com/pubs/pubs) - Pubs organizes your scientific papers together with their bibliographic data and provides command line access to basic and advanced manipulation of your library.
* [slr-kit](https://github.com/robolab-pavia/slr-kit) - Set of CLI tools to assist the writing of Systematic Literature Reviews powered by Natural Language Processing.

## <a name="security"></a>Security and encryption

* [cipher](https://github.com/ash-shell/cipher) - An Ash module that makes it easy to perform aes-256-cbc encryption for files and directories.  
* [encfs](http://www.arg0.net/#!encfs/c1awt) - Encrypted filesystem in user-space based on [FUSE](https://it.wikipedia.org/wiki/FUSE); mounts an encrypted directory into a clear one.  
* [Firejail](https://firejail.wordpress.com/) - A SUID program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces and seccomp-bpf.
* [GnuPG](https://gnupg.org/) - GnuPG is a complete and free implementation of the OpenPGP standard as defined by RFC4880 (also known as PGP).
* [hashcat](https://hashcat.net/hashcat/) - A robust and efficient password cracking tool that can help you recover lost passwords, audit password security, benchmark, or just figure out what data is stored in a hash.
* [LUKS](https://guardianproject.info/code/luks/) - Hard disk encryption tool; it stores all setup information in the partition header, enabling easy data transport or migration.
* [ots](https://github.com/sniptt-official/ots) - Share end-to-end encrypted secrets with others via a one-time URL.
* [uacme](https://github.com/ndilieto/uacme) - ACMEv2 client written in plain C with minimal dependencies.
* [wifi-password](https://github.com/rauchg/wifi-password) - Get wifi pass.

## <a name="shells"></a>Shells

* [Bash](https://www.gnu.org/software/bash/) - (Bourne Again SHell) The most widespread system shell to date.  
* [Fish](https://fishshell.com/) - "A command line shell for the 90s"; focused on user-friendliness, with powerful autosuggestions, colors, "sane scripting" (w.r.t. to Bash).
* [Spaceship](https://spaceship-prompt.sh/) - Minimalistic, powerful and extremely customizable Zsh prompt.
* [xonsh](https://xon.sh/) - The xonsh shell lets you easily mix Python and shell commands in a powerful and simplified approach to the command line.
* [Zsh](http://www.zsh.org/) - Alternative shell designed for interactive use.  

## <a name="music"></a>Sound and music

* [Alsamixer](http://www.alsa-project.org/main/index.php/Main_Page) - ALSA mixer with curses interfaces.  
* [beets](https://github.com/beetbox/beets) - Beets is the media library management system for obsessive music geeks: catalogs your collection, automatically improving its metadata as it goes.
* [castero](https://github.com/xgi/castero) - A TUI podcast client for the terminal.
* [cmus](https://cmus.github.io/) - A fast and lightweight audio player with configurable keybindings and playlist support.  
* [dzr](https://github.com/yne/dzr) - Command Line deezer.com Player for Linux, BSD, Android, Windows.
* [espeak](http://espeak.sourceforge.net/) - A compact open source software speech synthesizer for English and other languages.
* [Instant Music Downloader](https://github.com/yask123/Instant-Music-Downloader) - Instantly download any song!
* [kord](https://github.com/synestematic/kord) - A python framework that provides programmers with a simple api for the creation of music-based applications.
* [MOC](https://moc.daper.net/) - (music on console) is a powerful and easy to use console audio player; user interface a la Midnight Commander; plenty of features; fully controllable from the keyboard.  
* [Mp3blaster](http://www.mp3blaster.org/?m=1) - Audio player for the text console.
* [mpg123](http://mpg123.org/) - Quick `mp3` sound file player; no visual interface, just a command-line audio file player for `mp3` files.
* [mps-youtube](https://github.com/mps-youtube/mps-youtube) - A curses player for music tracks from Youtube; it allows to search for songs and playlists; it downloads the video, extracts the audio track and plays it; handles local playlists and many configuration parameters.
* [muCLIar](https://github.com/aayush1205/muCLIar) - YouTube automator bringing you your music right on your CLI.
* [MusicPlayerPlus](https://github.com/doctorfree/MusicPlayerPlus) - Featureful ncurses based MPD client inspired by ncmpc with integration for Beets, spectrum visualization,Bandcamp/Soundcloud, asciimatics, cantata, and more.
* [musikcube](https://github.com/clangen/musikcube) - A cross-platform, terminal-based audio engine, library, player and server written in C++.
* [ncmpcpp](https://rybczak.net/ncmpcpp/) - NCurses Music Player Client (Plus Plus) - featureful ncurses based MPD client inspired by ncmpc. Relevant features: tag editor, playlist editor, easy to use search engine, media library, music visualizer, ability to fetch artist info from [last.fm](https://www.last.fm/), new display mode, alternative user interface, ability to browse and add files from outside of MPD music directory.
* [ogg123](https://www.xiph.org/downloads/) - Quick `ogg` sound file player; no visual interface, just a command-line audio file player for the free and open `ogg` file format.
* [Siren](https://www.kariliq.nl/siren/) - Siren is a text-based audio player for UNIX-like operating systems.
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) - A Spotify client for the terminal written in Rust.
* [spotify-player](https://github.com/aome510/spotify-player) - spotify-player is a fast, easy to use, and configurable terminal music player having feature parity with the official Spotify application.
* [Tera](https://github.com/shinokada/tera) - Terminal Radio: an easy-to-use CLI music player to play favorite music, radio stations and explore various radio stations from the terminal only.
* [termusic](https://github.com/tramhao/termusic) - Terminal Music Player written in Rust.
* [Tizonia](https://github.com/tizonia/tizonia-openmax-il) - Command-line cloud music player for Linux with support for Spotify, Google Play Music, YouTube, SoundCloud, TuneIn, iHeartRadio, Plex servers and Chromecast devices.
* [yt-audio](https://github.com/pseudoroot/yt-audio) - A simple, configurable youtube-dl wrapper to download and manage youtube audio.

## <a name="monitor"></a>System monitoring

* [below](https://github.com/facebookincubator/below) - A time traveling resource monitor for modern Linux systems
* [bpytop](https://github.com/aristocratos/bpytop) - Linux/OSX/FreeBSD resource monitor with a nice interface.
* [dmidecode](https://www.nongnu.org/dmidecode/) - System information utility.
* [glances](https://github.com/nicolargo/glances) - A comprehensive and detailed system monitoring tool; monitored parameters include: CPU, memory, load, process list, network interfaces, disk I/O, sensors, filesystems, docker, system info, uptime.
* [htop](http://hisham.hm/htop/) - An interactive process viewer for Unix; improves the UI of `top`, by adding real-time meters and colors.
* [hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool.
* [inxi](http://smxi.org/docs/inxi.htm) - A comprehensive system information script; provides information about CPU, graphics, audio and network devices, drives and partitions, sensors; implemented as a Bash script.
* [iotop](http://guichaz.free.fr/iotop/) - "A Python program with a top like UI used to show of behalf of which process is the I/O going on".
* [lfs](https://github.com/Canop/lfs) - A thing to get information on your mounted disks
* [multitail](https://www.vanheusden.com/multitail/) - A command to open multiple log files in a single terminal window and monitor them in real-time.  
* [neofetch](https://github.com/dylanaraps/neofetch) - Neofetch is a CLI system information tool written in BASH. Neofetch displays information about your system next to an image, your OS logo, or any ASCII file of your choice.
* [ngrep](http://ngrep.sourceforge.net/) - (Network grep) applies the `grep` logic to the network layer, allowing to match regular expressions against data payloads of packets; it recognizes IPv4/6, TCP, UDP, ICMPv4/6, IGMP and Raw across Ethernet, PPP, SLIP, FDDI, Token Ring and null interfaces.
* [noti](https://github.com/variadico/noti) - Monitor a process and trigger a notification.
* [powertop](https://01.org/powertop) - A `top`-like utility to monitor the sources of power consumption; allows to turn on/off many components; quite useful to track possible power-related issues.  
* [screenFetch](https://github.com/KittyKatt/screenFetch) - It can be used to generate one of those nifty terminal theme information + ASCII distribution logos. It auto-detects the distribution and display an ASCII version of that distribution's logo and some valuable information to the right.
* [smem](https://www.selenic.com/smem/) - Python program that reports memory usage; it can report the "proportional set size" (PSS), a meaningful representation of the amount of memory used by libraries and applications in a virtual memory system; it has built-in chart generation.
* [sysdig](https://www.sysdig.org/) - Sysdig captures system calls and events from the Linux kernel.  You can save, filter, and analyze the data with our CLI or our desktop app.  Think of sysdig as strace + tcpdump + htop + iftop + lsof + wireshark for your entire system.
* [The Logfile Navigator](https://lnav.org/) - An advanced and colorful log file viewer with TUI interface.
* [tiptop](https://github.com/nschloe/tiptop) - A command-line system monitoring tool in the spirit of top, written in Python. It displays various interesting system stats and graphs them. Works on all operating systems.
* [top](http://www.unixtop.org/) - The classical Unix utility that provides a rolling display of top cpu using processes.  
* [ttyload](http://www.daveltd.com/src/util/ttyload/) - ttyload is a lightweight utility which is intended to offer a color-coded graph of load averages over time on Linux and other Unix-like systems. It enables a graphical tracking of system load average in a terminal (“tty“).
* [watch](http://www.linfo.org/watch.html) - Periodically runs a command in the console while temporarily clearing the screen content; it makes it easy to check differences between the output of two subsequent commands; it provides "diff" functionality to highlight the changing characters between outputs.
* [watcher](https://github.com/sethigeet/watcher) - Watches all the files present in a directory and whenever a file is changed or a file is created/deleted from the directory, it runs a specified command.
* [whowatch](https://www.tecmint.com/whowatch-monitor-linux-users-and-processes-in-real-time/) - Monitor Linux Users and Processes in Real Time.
* [wtf](https://github.com/wtfutil/wtf) - The personal information dashboard for your terminal.
* [ytop](https://github.com/cjbassi/ytop) - TUI system monitor written in Rust.

## <a name="system"></a>System tools

* [atuin](https://github.com/ellie/atuin) - Atuin replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [Bevel](https://github.com/NorfairKing/bevel) - Command line history in an SQLite database for effective re-use.
* [bin](https://github.com/marcosnils/bin) - Manages binary files downloaded from different sources.
* [brightnessctl](https://github.com/Hummer12007/brightnessctl) - Read and control device brightness. Devices, by default, include backlight and LEDs - searched for in corresponding classes.
* [conspy](http://conspy.sourceforge.net/) - "Conspy allows a (possibly remote) user to see what is displayed on a Linux virtual console, and send keystrokes to it." 
* [ContainerSSH](https://github.com/ContainerSSH/ContainerSSH) - An SSH Server that Launches Containers in Kubernetes and Docker on demand.
* [Devbox](https://github.com/jetpack-io/devbox) - Devbox is a command-line tool that lets you easily create isolated shells and containers by defining the list of packages required by the environment.
* [docker](https://docs.docker.com/) - Self-sufficient runtime for containers.
* [fkill-cli](https://github.com/sindresorhus/fkill-cli) - Simple cross-platform process killer.
* [has](https://github.com/kdabir/has) - Checks presence of various command line tools on the PATH and reports their installed version.
* [hstr](https://github.com/dvorka/hstr) - A tool for managing the history; powerful visual search and execution of previous commands; history editing capabilities.  
* [lshw](http://www.ezix.org/project/wiki/HardwareLiSter) - A small tool to provide detailed information on the hardware configuration of the machine. It can report exact memory configuration, firmware version, mainboard configuration, CPU version and speed, cache configuration, bus speed, etc.
* [mackup](https://github.com/lra/mackup) - Keep your application settings in sync (OS X/Linux).
* [nala](https://gitlab.com/volian/nala) - apt package manager front-end with cleaner interface.
* [Ntfy](https://github.com/dschep/ntfy) - Cross-platform Python utility that enables you to automatically get desktop notifications on demand or when long running commands complete. It can as well send push notifications to your phone once a particular command completes.
* [parallel](https://www.gnu.org/software/parallel/) - A shell tool from GNU for executing jobs in parallel using one or more computers; it can split the input and pipe it into commands in parallel.  
* [pulsemixer](https://github.com/GeorgeFilipkin/pulsemixer) - CLI and curses mixer for PulseAudio.
* [stew](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
* [task-spooler](http://vicerveza.homeunix.net/~viric/soft/ts/) - A Unix batch system that can be used to add the Linux commands to the queue and execute them one after the other in numerical order (ascending order, to be precise). This can be very useful when you have to run a lots of commands, but you don't want to waste time waiting for one command to finish and run the next command. You can queue it all up and Task Spooler will execute them one by one. In the mean time, you can do other activities.

## <a name="terminal"></a>Terminals

* [byobu](http://byobu.co/) - A text-based window manager and terminal multiplexer; it features enhanced profiles, convenient keybindings, configuration utilities, and toggle-able system status notifications; compatible with `screen` and `tmux`.
* [dtach](https://github.com/crigler/dtach) - A program written in C that emulates the detach feature of screen.
* [mtm](https://github.com/deadpixi/mtm) - Micro Terminal Multiplexer - Simple but usable, stable and minimalistic terminal multiplexer.
* [mx](https://gitlab.com/lpireyn/mx) - A tmux session manager written as a single Bash script.
* [screen](https://www.gnu.org/software/screen/) - Terminal multiplexer that split a physical terminal between several processes, typically interactive shells.
* [Tmate](https://tmate.io/) - A fork of tmux that allows to share the terminal with other users. AFAIK, it connects to a centralized server to establish the connection. Someone may see this inconvenient for privacy issues.
* [tmux](https://github.com/tmux/tmux) - Terminal multiplexer; born to improve `screen`; client-server architecture, `vi` and `emacs` key-bindings, search in window feature and many more.
* [warp](https://github.com/spolu/warp) - Secure and simple terminal sharing.  
* [Zellij](https://github.com/zellij-org/zellij) - A workspace aimed at developers, ops-oriented people and anyone who loves the terminal. At its core, it is a terminal multiplexer.

## <a name="text-processing"></a>Text processing

* [Aewan](http://aewan.sourceforge.net/) - Aewan is a multi-layered ASCII graphics/animation editor. It produces stand-alone cat-able ASCII art files and an easy-to-parse format for integration into terminal applications.
* [amber](https://github.com/dalance/amber) - Code search / replace tool.
* [anew](https://github.com/tomnomnom/anew) - Tool for adding new lines to files, skipping duplicates.
* [brok](https://github.com/smallhadroncollider/brok) - Find broken links in text documents.
* [ccat](https://github.com/jingweno/ccat) - A `cat` command with colorized output.  
* [choose](https://github.com/jagprog5/choose) - NCurses based token selector with a nice terminal user interface for selecting tokens. Selecting a line from the bash history is only one of its use cases.
* [deadlink](https://github.com/nschloe/deadlink) - Parses text files for HTTP URLs and checks if they are still valid. Good to use on markdown documentation files.
* [delta](https://github.com/dandavison/delta) - A syntax-highlighter for git and diff output.
* [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - Make your diffs human readable instead of machine readable.
* [Difftastic](https://github.com/Wilfred/difftastic) - Syntax-aware structured diff tool.
* [espanso](https://github.com/federico-terzi/espanso) - Cross-platform Text Expander written in Rust. Not limited to the command line.
* [fastmod](https://github.com/facebookincubator/fastmod) - A tool to assist you with large-scale codebase refactors, and it supports most of codemod's options. It is focused on improving the use case "I want to use interactive mode to make sure my regex is correct, and then I want to apply the regex everywhere".
* [fzf](https://github.com/junegunn/fzf) - (FuZzy Finder) is a general-purpose command-line finder with fuzzy search/filter capabilities; good integration with `vim`.  
* [fzy](https://github.com/jhawthorn/fzy) - Better fuzzy finder.
* [grc](https://github.com/pengwynn/grc) - (Generic Colouriser) can be configured to parse a given text stream and to colorize it according to regexp written in configuration files; different patterns can be associated to file types.  
* [hck](https://github.com/sstadick/hck) - A sharp cut clone.
* [huniq](https://github.com/koraa/huniq) - Command line utility to remove duplicates from the given input. Note that huniq does not sort the input, it just removes duplicates.
* [LinuxLogo](https://sourceforge.net/projects/linuxlogo/) - Display the Linux distribution logo in ASCII format.
* [lolcat](https://github.com/busyloop/lolcat) - Ruby Gem to colorize the output of the cat command.
* [luneta](https://github.com/fbeline/luneta) - Interactive filter that can be easily composed within any script.
* [pdf-diff](https://github.com/serhack/pdf-diff) - A tool for visualizing differences between two pdf files. Mainly dedicated to editors that usually spends a lot of hours on several pdf.
* [percol](https://github.com/mooz/percol) - A Python script that "1) receives input lines from `stdin` or a file, 2) lists the input lines and waits for input that filter/select the line(s), 3) outputs the selected line(s) to `stdout`"; can be used to add interactivity to many regular shell commands.
* [pick](https://github.com/calleerlandsson/pick) - Utility that allows users to choose one option from a set of choices using an interface with fuzzy search functionality.  
* [pv](http://www.ivarch.com/programs/pv.shtml) - The pv command is used to monitor the progress of data through pipe.
* [rare](https://github.com/zix99/rare) - Realtime regex-extraction and aggregation into common formats such as histograms, bar graphs, numerical summaries, tables, and more!
* [sd](https://github.com/chmln/sd) - s[earch] & d[isplace] - An intuitive find & replace CLI; a possible replacement for sed.
* [skim](https://github.com/lotabout/skim) - Fuzzy Finder in rust.
* [squeeze](https://github.com/aymericbeaumet/squeeze) - Enables to extract rich information from any text (raw, JSON, HTML, YAML, etc).
* [teip](https://github.com/greymd/teip) - Select partial standard input and replace with the result of another command.
* [tuc](https://github.com/riquito/tuc) - You want to cut on more than just a character, perhaps using negative indexes or format the selected fields as you want... Maybe you want to cut on lines (ever needed to drop first and last line?)... That's where tuc can help.
* [Ultimate Plumber](https://github.com/akavel/up) - Helps to interactively and incrementally explore textual data in Linux, by making it easier to quickly build complex pipelines, thanks to a fast feedback loop.
* [ydiff](https://github.com/ymattw/ydiff) - View colored, incremental diff.

## <a name="text-search"></a>Text search

* [ack](http://beyondgrep.com/) - A tool like `grep` optimized for programmers; written in Perl, it speeds up searches thanks to skipping non interesting directories, such as `.git`.
* [ag](https://github.com/ggreer/the_silver_searcher) - (The silver searcher) is a text search utility targeted to source code; it skips versioning systems data directories; it is inspired by `ack`, but faster.
* [jiq](https://github.com/fiatjaf/jiq) - jid on jq - interactive JSON query tool using jq expressions.
* [paragrep](http://software.clapper.org/paragrep/) - Greps regular expressions in a text file(s) and prints out the paragraphs containing those expressions; a paragraph is defined as a block of text delimited by an empty or blank line; fully customizable via command line parameters.  
* [ripgrep](https://github.com/BurntSushi/ripgrep) - Recursively searches directories for a regex pattern.
* [ripgrep-all](https://github.com/phiresky/ripgrep-all) - grep in text files but also search in PDFs, E-Books, office documents, zip, tar.gz, etc.
* [sift](https://sift-tool.org/) - Fast and powerful open source alternative to grep; it targets flexibility and performance: can be as fast as "regular" grep and allows to specify complex expressions to find text.
* [todocheck](https://github.com/preslavmihaylov/todocheck) - Static code analyzer for annotated TODO comments.
* [vgrep](https://github.com/vrothberg/vgrep) - User-friendly pager for grep.

## <a name="todo-manager"></a>Todo managers

* [CLI-Manager](https://github.com/MikyStar/CLI-Manager) - Command Line Interface for managing tasks locally on the fly.
* [dstask](https://github.com/naggie/dstask) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task.
* [grit](https://github.com/climech/grit) - A multitree-based personal task manager.
* [iKog](https://sites.google.com/site/henspace/ikog/) - A fully-featured task manager incapsulated within a Python script (just carry around the script to retain all the TODOs). When the script is run, a Python shell is opened, where task-related commands can be entered (ADD, LIST, etc.); a pity that commands are uppercase, which requires the annoying use of the Shift key.
* [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat.
* [taskell](https://github.com/smallhadroncollider/taskell) - Interactive kanban board/task manager.
* [TaskWarrior](https://taskwarrior.org/) - Todo manager with advanced features; dedicated synchronization server available; many plugins and related tools; healthy software project.  
* [todo.txt](http://todotxt.org/) - Minimalistic todo manager that uses a simple plain text file to keep track of items; implemented as a shell script.  
* [todolist](http://todolist.site/) - A minimal clone of [Wunderlist](https://www.wunderlist.com/), with 30% of its features. GTD oriented. It stores the task list in a hidden JSON file in the home directory, making it easy to backup or share them.
* [todotxt-machine](https://pypi.org/project/todotxt-machine/) - Interfacce for todo.txt.
* [tsk](https://github.com/kakengloh/tsk) - Terminal task management app with an emphasis on simplicity, efficiency and ease of use.
* [TuDu](https://code.meskio.net/tudu/) - A comand line interface to manage hierarchical todos.  Each task has a title, a long text description, a deadline (tudu warns you when the date is close), and a scheduled date. There are categories and priorities.
* [xit](https://github.com/jotaen/xit) - A plain-text file format for todos and check lists. So, not really a program, but I believe it is worth to list :-)
* [Yokadi](https://yokadi.github.io/) - Project-based todo manager: every task must be specified with a mandatory project indication. Tasks are stored within a SQLlite DB. Written in Python.  

## <a name="utility"></a>Utilities

* [asciinema](https://github.com/asciinema/asciinema) - Terminal session recorder.
* [Cloudcash](https://github.com/mrusme/cloudcash) - Check your cloud spending from the CLI, from Waybar, and from the macOS menu bar!
* [cointop](https://github.com/cointop-sh/cointop) - A fast and lightweight interactive terminal based UI application for tracking cryptocurrencies.
* [dasht](http://sunaku.github.io/dasht/man/man0/README.html) - Search API docs offline, in your terminal or browser.
* [dateutils](http://www.fresse.org/dateutils/) - Dateutils are a bunch of tools that revolve around fiddling with dates and times in the command line with a strong focus on use cases that arise when dealing with large amounts of financial data.
* [eg](https://github.com/srsudar/eg) - Useful examples at the command line.
* [Gaze](https://github.com/wtetsu/gaze) - Runs a command, right after you save a file.
* [GoTTY](https://github.com/yudai/gotty) - A program to turn CLI tools into web applications; basically, it runs a command and starts a server so that the output can be displayed in a web page.
* [just](https://github.com/casey/just) - Handy way to save and run project-specific commands.
* [kmdr-cli](https://github.com/ediardo/kmdr-cli#supported-programs) - The CLI tool for explaining commands from your terminal.
* [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line.
* [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner.
* [pbgopy](https://github.com/nakabonne/pbgopy) - Copy and paste between devices.
* [pdd](https://github.com/jarun/pdd) - Tiny date, time diff calculator.
* [pmenu](https://github.com/sgtpep/pmenu) - A dynamic terminal-based menu inspired by dmenu.
* [powerline](https://github.com/powerline/powerline) - Powerline is a statusline plugin for vim, and provides statuslines and prompts for several other applications, including zsh, bash, tmux, IPython, Awesome and Qtile.
* [rofi](https://github.com/davatorium/rofi) - A window switcher, application launcher and dmenu replacement.
* [Starship](https://starship.rs/) - The cross-shell prompt for astronauts.
* [tealdeer](https://github.com/dbrgn/tealdeer) - Very fast implementation of tldr in Rust.
* [termsaver](http://termsaver.brunobraga.net/) - termsaver to enjoy fancy ASCII screensavers like matrix, clock, starwars, and a couple of not-safe-for-work screens.
* [Viddy](https://github.com/sachaos/viddy) - Modern watch command. Time machine and pager etc.
* [yank](https://github.com/mptre/yank) - Reads input from stdin and display a selection interface that allows a field to be selected and copied to the clipboard.

## <a name="versioning"></a>Versioning

* [Bazaar](http://bazaar.canonical.com/en/) - Multiplatform version control system supporting diffferent workflows; it is part of the GNU Project, and it is free software sponsored by Canonical.
* [fossil](https://fossil-scm.org/) - A simple, high-reliability, distributed software configuration management system with these advanced features: project management, built-in web interface, friendly self-hosting, simple networking, all-in-one standalone executable, and much more.
* [gee](https://github.com/human37/gee) - CLI repository manager and automation tool written in rust.
* [Gistup](https://github.com/mbostock/gistup) - Create a gist from terminal, then use git to update it.
* [Mercurial](https://www.mercurial-scm.org/) - Free, distributed source control management tool.

## <a name="viewers"></a>Viewers

* [bat](https://github.com/sharkdp/bat) - A cat clone with syntax highlighting and Git integration.
* [cacaview](http://caca.zoy.org/wiki/libcaca) - A library and a program to display JPG, PNG, GIF or BMP images in the terminal using ASCII characters.
* [feh](https://feh.finalrewind.org/) - "X11 image viewer aimed mostly at console users" (cit.); with no fancy GUI, it is controlled via commandline arguments and configurable key/mouse actions.
* [fx](https://github.com/antonmedv/fx) - Command-line JSON viewer.
* [glow](https://github.com/charmbracelet/glow) - Render markdown on the CLI, with pizzazz!
* [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor: A Hacker News command line interface (CLI).
* [hexyl](https://github.com/sharkdp/hexyl) - Command-line hex viewer.
* [jc](https://github.com/kellyjonbrazil/jc) - Serializes the output of command line tools to JSON.
* [jless](https://pauljuliusmartinez.github.io/) - Command-line JSON viewer designed for reading, exploring, and searching through JSON data.
* [jqview](https://github.com/fiatjaf/jqview) - Simplest possible native GUI for inspecting JSON.
* [mdt](https://github.com/robolab-pavia/mdt) - MarkDown in the Terminal. A markdown viewer with themes defined by JSON files and interactive mode to open links and word-wrapping adaptable to the terminal width.
* [mplayer](http://www.mplayerhq.hu/design7/news.html) - One of the most popular video/audio players around; plays most audio and video formats (using ASCII characters) in the shell; provides a GUI for graphical visualization.  
* [mpv](https://mpv.io/) - A cross-platform media player with many features such as frame timing, MKV chapters and subtitles. It is a responsive video player with minimal layout customizable with themes. A good alternative media player to VLC since it can handle almost all the media formats as VLC, but using much less resources.
* [mupdf](http://mupdf.com/) - Lightweight graphical PDF visualizer; strong key-based control; fast and accurate rendering.  
* [ov](https://github.com/noborus/ov) - Feature-rich terminal-based text viewer.
* [tabview](https://github.com/TabViewer/tabview) - Python curses command line CSV and tabular data viewer.
* [Terminal Markdown Viewer](https://github.com/axiros/terminal_markdown_viewer) - Python based Markdown viewer for the terminal.
* [TerminalImageViewer](https://github.com/stefanhaustein/TerminalImageViewer) - Small C++ program to display images in a (modern) terminal using RGB ANSI codes and unicode block graphics characters.
* [termv](https://github.com/Roshan-R/termv) - A terminal iptv player written in bash.
* [texel](https://github.com/Lauriat/texel) - Command line interface for reading spreadsheets inside terminal.
* [TV](https://github.com/alexhallam/tv) - Cross-platform CSV pretty printer made to maximize viewer enjoyment.
* [viu](https://github.com/learn-anything/command-line-tools) - Command-line application to view images from the terminal written in Rust.
* [youtube-viewer](https://github.com/trizen/youtube-viewer) - Lightweight application that searches and streams videos from YouTube.
* [zathura](https://pwmt.org/projects/zathura/) - Plugin based document file visualizer (PDF, DejaVu, PS); strongly key-based control.

## <a name="browser"></a>Web browser

* [Amfora](https://github.com/makeworld-the-better-one/amfora) - Amfora aims to be the best looking Gemini client with the most features. It does not support Gopher or other non-Web protocols.
* [asuka](https://git.sr.ht/~julienxx/asuka) - A Gemini Project client written in Rust with NCurses.
* [Bombadillo](https://bombadillo.colorfield.space/) - A non-web browser, designed for a growing list of protocols operating outside of the web. Currently supports Gemini, Finger and Gopher.
* [browsh](https://www.brow.sh/) - It renders anything that a modern browser can; HTML5, CSS3, JS, video and even WebGL. Its main purpose is to be run on a remote server and accessed via SSH/Mosh or the in-browser HTML service in order to significantly reduce bandwidth and thus both increase browsing speeds and decrease bandwidth costs.
* [cli-arxiv](https://github.com/knguyenanhoa/cli-arxiv) - CLI tool for exploring arXiv.
* [Elinks](http://elinks.cz/) - "Advanced and well-established feature-rich text mode web browser"; started as a fork of `Links`; it supports background download with queueing, some support from CSS, text box editing in external text editor.
* [gplaces](https://github.com/dimkr/gplaces) - Simple but powerful terminal Gemini client.
* [Graphene](https://github.com/atsepkov/Graphene) - A text-based web browser that's a joy to use.
* [Gremlin](https://github.com/actuday6418/gremlin) - Gemini browser for the terminal.
* [Links](http://www.jikos.cz/~mikulas/links//) - A textual Web browser with tables and frames.  
* [Lynx](http://lynx.invisible-island.net/) - A highly configurable text-based web browser; one of the oldest CLI browser I'm aware of.  
* [min](https://github.com/a-h/min) - A Gemini browser with Vim style keyboard navigation, client certificate support and history and bookmarks saved in TSV files.
* [Romulus](https://github.com/LukeEmmet/Romulus) - A cross platform Gemini console client in C# with a simple user interface, interactive menus and mouse support.
* [s](https://github.com/zquestz/s) - Web search from the terminal. Just opens in your browser.
* [Telescope](https://telescope.omarpolo.com/) - Gemini client with UI that is strongly inspired from Emacs and W3M.
* [w3m](http://w3m.sourceforge.net/) - A text-based web browser as well as a pager like `less`; it can be used as a text formatting tool which typesets HTML into plain text.  

## <a name="webdev"></a>Web development

* [ain](https://github.com/jonaslu/ain) - An HTTP API client for the terminal.
* [http-tanker](https://github.com/PierreKieffer/http-tanker) - Terminal application used for API testing; easily create, manage and execute http requests from the terminal.
* [Hugo](https://gohugo.io/) - The world’s fastest framework for building websites.
* [iola](https://github.com/pvarentsov/iola) - A command-line socket client with REST API. It helps to work with socket servers using your favorite REST client.
* [linkchecker](https://github.com/linkchecker/linkchecker) - Check links in web documents or full websites.
* [lychee](https://github.com/lycheeverse/lychee) - Fast, async, resource-friendly link checker written in Rust.
* [Metalsmith](http://www.metalsmith.io/) - An extremely simple static site generator; all functionalities are provided by plugins that can be combined and chained; written and extendable in Javascript.  
* [Mycorrhiza Wiki](https://github.com/bouncepaw/mycorrhiza) - A lightweight file-system wiki engine that uses Git for keeping history.
* [nanoc](http://nanoc.ws/) - Static site generator written in Ruby; extremely powerful and customizable; support many formats to generate HTML content.  
* [siege](https://www.joedog.org/siege-home/) - An http load testing and benchmarking utility designed to let web developers stress their code.  
* [snallygaster](https://github.com/hannob/snallygaster) - Tool to scan for secret files on HTTP servers.
* [Tsung](http://tsung.erlang-projects.org/) - A multi-protocol distributed load testing tool that can be used to stress HTTP, WebDAV, SOAP, PostgreSQL, MySQL, LDAP and Jabber/XMPP servers.
* [urlhunter](https://github.com/utkusen/urlhunter) - Recon tool that allows searching on URLs that are exposed via shortener services.


# <a name="resources"></a>Related resources

A list of some online resoures that contribute interesting links to apps and info.

[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - A wonderful summary from Joshua Levy regarding command line (Bash in particular) tools, programs, tips and tricks; contains many pointers to resources and repositories, in the form of "to do this you must know that", which gives great pointers but requires further investigation from different sources; translated in many languages.

[Inconsolation blog](https://inconsolation.wordpress.com/) - "Adventures with lightweight and minimalist software for Linux": reviews of many command-line programs; many programs reviewed (400+, at least), with screenshots and animated GIFs; the style of presentation is ironic and funny, but requires some effort to figure out the real contribution of a program.

[A little collection of cool unix terminal/console/curses tools](https://kkovacs.eu/cool-but-obscure-unix-tools) - "Some are little-known, some are just too useful to miss, some are pure obscure..." from Kristof Kovacs; nice list with screenshot; mostly oriented to system administration; unfortunately there are no clickable links.

[Caleb Xu shell awesome](https://github.com/alebcay/awesome-shell) - Focused on UNIX shell tools.

[Adam Harris awesome CLI apps](https://github.com/aharris88/awesome-cli-apps) - Nice list of tools; somehow too much Javascript/Node.js-centered for my tastes.

[Marcel Bischoff awesome commandd line apps](https://github.com/herrbischoff/awesome-command-line-apps) - Nice up-to-date list of useful tools.

[Awesome CLI by sintaxi](https://github.com/sintaxi/awesome-cli/blob/master/README.md) - Relatively short list with short descriptions; with some original entries.



