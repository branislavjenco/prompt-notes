# Notes
A simple bash function that lets you add a short note to an ever growing notes.txt file.

# Installation
Add the function to your `.bashrc` or `.bash_aliases` and change the location of the notes file as necessary. I keep it in Dropbox. Then `source .bashrc` (or `source .bash_aliases`).

# Use
`note <some-text>` to add a string of text to the end of the notes file. The script always makes a new line and prepends the current date.
`note -o <some-text>` same thing, but the script also opens vim at the end of the text file. Useful if you want add more text, which is nicer to do in a text editor. 

# Idea for extension

Show the beginning of last entry in the terminal prompt. This could be useful for todos or for keeping track of what one is working on. Might be too annoying though. It might also be conflating a "todo" list with a "done" list.
