# calli

**Note! This code currently adds nothing to existing code, please don't think
I'm  passing it along as my own work.** I plan to eventually modify and expand
on it. The repo will be made private if I abandon it before making significant
changes to it.


First thing first, I have no clue what I'm doing. This is a project intended to
teach me just a little bit about, hopefully, a few things. Calli is a simple
text editor based on snaptoken's [instructional
booklet](https://viewsourcecode.org/snaptoken/kilo/index.html) implementing
antirez's [kilo](https://antirez.com/news/108) text editor. In its current
state, calli is no different than snaptoken's code as I am still working
through kilo.

Why am I doing this? Because I like neovim and want to see how text editors.

How will it be different than kilo? I don't know at the moment.

Where does the name come from? It's named after my late cat Calli, who's name
is based on Calliope, a prominent Greek Muse of epic poetry and eloquence in
Greek Mythology.


# Issues 

- [ ] Currently, 'q' is used to exit the program. Ideally it would be something
like Ctrl + q which is what kilo uses. This is easy on Windows since 0x1F is a
control character produced by Ctrl + '_', hence, pressing Ctrl + q would
produce (0x1F & 0x71 = 0x11), where 0x71 is the ANSI Hex code for 'q'. We could
then direct the program to exit when processing 0x11. This is not the same on
macOS, so we'll need to find some other way.

# Todo

- [ ] Figure out how to allow multiple modes, e.g., "insert mode" and "normal
  mode."
- [ ] Line numbering.
- [ ] Jump to text.
- [ ] Display information on the bottom few lines, e.g., current file, current
  mode. I know how to do this with escape commands, but maybe there are other
  ways? 

  ...

- [ ] Many more.


