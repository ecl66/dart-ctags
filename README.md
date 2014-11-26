# Vim compatible tags file for dart

## Example

```
cd ~/dev/dart-ctags
pub global activate -s path .
cd ~/dev/your-dart-project
pub global run dart_ctags:tags.dart -o .git/tags
```

## Help

```
pub global run dart_ctags:tags.dart -h
Usage:
  pub global run dart_ctags:tags.dart [OPTIONS] [FILES...]
  pub run tags.dart [OPTIONS] [FILES...]

-o, --output=<FILE>     Output file for tags (default: stdout)
    --follow-links      Follow symbolic links (default: false)
    --include-hidden    Include hidden directories (default: false)
-l, --line-numbers      Add line numbers to extension fields (default: false)
    --skip-sort         Skip sorting the output (default: false)
-h, --help              Show this help
```
