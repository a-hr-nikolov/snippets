# Personal snippets for various languages

Here you can find the snippets I use for different languages. If the repository is rather empty-looking, that's because I have not migrated all of my snippets yet.

## Installation

### Linux:

The simplest way to "install" the snippets is to clone the repo and symlink the entire directory within `~/.config/Code/User/snippets` .

Alternatively, link individual files there.

### Other:

I have no idea, but I'm pretty sure there must be an equivalent file system hierarchy, where you can just shortcut the snippets directory.

## Why not use snippet extensions?

I prefer to use my own snippets in addition to (or sometimes in place of) snippet extensions for a couple of reasons.

1. **Better ergonomics per my individual use case** - I prefer my most common snippets to be easy to type (often with one hand). I also prefer to have my own mnemonics.
2. **Personalization** - Most snippets are a tad too general and can be extended further. For example, in Go an `err != nil` snippet will typically only include the if statement, while I've defined a bunch of snippets for different use cases (returning errors, wrapping errors, printing errors, having vals alongside errors, etc.).
3. **Portability** - If I want to try a different IDE or editor, as long as it supports some structured snippet format, I can easily convert the JSON snippets for use there. I cannot do so easily with external extensions, unless I want to bother with maintaining a code repo for all of them individually. At which point why not simply have my own snippets?

## Languages

I plan to have snippets for the following languages at some point

1. Go
2. Python (+Django, +FastAPI)
3. SQL
4. JavaScript / TypeScript
