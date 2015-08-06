# repl-require

Automatically load modules into your repl's scope.

### Installation & use

You can simply install this module globally using `npm install -g repl-require`.

Then, to enter a node repl with your modules use `noder` (or make your own alias)

### How do I specify modules?

Create a file in your home directory called `.noderc` which includes a newline delimited list of modules to include, e.g:

```
lo=lodash
async
req=request
```
