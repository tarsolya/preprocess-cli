preprocess-cli
==========

CLI wrapper for [preprocess](https://github.com/jsoverson/preprocess).

Usage
-----
```
Usage: preprocess <file> [options]

Options:
  -o, --output-file                 Output file                                                               
  -s, --file-not-found-silent-fail  Instruct preprocess to fail silently.                                       [default: false]
  --src-dir                         The directory where to look for files included. Defaults to process.cwd().
  --src-eol                         The end of line (EOL) character to use for the preprocessed result.       
  -t, --type                        The syntax type of source string to preprocess.                             [default: "html"]
  -c, --context                     Context file: must be js or json. Defaults to process.env.     
```

License
-------
Released under permissive MIT License.
