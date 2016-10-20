# pcol
Command `pcol` is just a shortcut of `awk '{print $<index>}'`,
to make it easy to extract a column of input text.

## Usage
pcol index [splitter]

- Index is an index number of the column you want.
- Splitter is a string to split the text.
- Index and splitter must follow `awk`'s format.

Note that you have to put input texts from `stdin`.

## Install
Copy `pcol` file to your `$PATH`(`/usr/local/bin`...etc).

## License
3 clause BSD.
See `LICENSE` file.
