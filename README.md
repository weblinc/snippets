# Weblinc Snippets

A collection of useful text-editor snippets for the WebLinc platform.


## Snippet Packages

Follow the links below to see what snippets we offer

- [Sublime Text](https://github.com/weblinc/snippets/tree/sublime)


## Installation

### Sublime Text 3 - OS X

```
cd "~/Library/Application Support/Sublime Text 3/Packages/User"
git clone git@github.com:weblinc/snippets.git
cd snippets
git checkout sublime
```

## Branching

The `sublime` branch contains snippets for the most recent version of WebLinc.

The `sublime-v2` branch contains snippts specific for any v2.x version of WebLinc.


## Contributing

This repo is structured a bit differently. The `master` branch contains only this README.md file, which contains links to each snippet package. The snippet package lives in a branch, named after the text editor with which the snippets are compatible.

For example, if you had a new snippet to offer for Sublime Text, you'd work within the `sublime` branch.

Conversely, if you use Text Mate and there is no corresponding branch, you would create a new branch called `textmate` and work in that branch to produce the snippet offering. Finally, this README.md file should contain links to all offered branches, plus any installation documentation specific to the new text editor.

