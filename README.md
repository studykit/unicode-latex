# Unicode Latex for vscode

This is a fork of [ojsheikh/unicode-latex](https://github.com/ojsheikh/unicode-latex). 

A visual studio code extension that allows the insertion of unicode symbols from the latex names of those symbols. The list of symbols is currently generated from the Julia programming language's REPL's latex completions.

## Usage

When editing a plaintext file, this extension provides autocompletions for latex symbols - inserting the equivalent unicode character for the selected completion. Completions are triggered on ','.

To insert a symbol, simply execute the `Unicode: Insert Math Symbol` command and type in the name of your desired symbol or select it from the drop-down list.

![Insertion Demo](https://raw.githubusercontent.com/oijazsh/unicode-latex/master/demo-insert.gif)
