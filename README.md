# generate_diff
Bash script to assist the [latexdiff](https://ctan.org/pkg/latexdiff) program. Particularly useful when going through the revision processes for an academic journal. See the examples folder for a full example.

# Usage

To use generate_diff, follow these instructions:

1. copy the generate_diff file into an appropriate folder
2. give generate_diff permission to run (e.g. via `chmod +x generate_diff in the terminal)
3. edit (using any text editor) top lines within generate_diff to reflect your specific new and old folder names
4. run generate_diff (e.g. in terminal `./generate_diff`)

`generate_diff` has some assumptions about the structure of your latex projects:

+ all file/pathnames contain no spaces
+ all figures are located in a subdirectory called "figures"