## [markdown-html](https://atom.io/packages/markdown-html)

Convert markdown-formatted documents to html without ever leaving Atom.

### Usage
Just focus the window containing your markdown file and use the `convert` command.

### How it works

The HTML provided by running the markdown through [marked](https://www.npmjs.org/package/marked) is prepended with the css from the [markdown-preview atom package](https://github.com/atom/markdown-preview). The syntax-highlights styling is pulled from the user's currently-active theme and added in the same way.

The package has dependencies on [tree-view](https://github.com/atom/tree-view) and [markdown-preview](https://github.com/atom/markdown-preview), but since these are included in the default atom installation, you probably won't have to worry about that.

#### Heart it? Hate it?
Feel free to run `apm star 'markdown-html'` or give some feedback :smile:
