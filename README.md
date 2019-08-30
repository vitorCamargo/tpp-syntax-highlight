# T++ Syntax Highlight Extension
This is an extension for T++ Programming Language Syntax Highlighting.

## How to Use
In this repository there is an file called: ***tpp-extension.vsix***, to run this extension you have to go to *VS Code* and in the tab 'Extensions' click in the 'Install from ***VSIX***...'

## The First Steps
To create a new extension for *VS Code*, it is need to run the following command to install the dependencies:
```sh
npm install -g yo generator-code vsce
```

and:
```sh
yo code
```

to create the initial structure for the ***New Language Support*** Extension.

After putting everthing we want to the new programming language, you need to create the *.vsix* file, using the command:
```sh
vsce package
```