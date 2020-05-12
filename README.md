# Visual Studio Code Extensions

## Export installed extensions
To export installed extensions to a file, perform the following:
```bash
code --list-extensions | xargs -L 1 echo code --install-extension > <target_file>
```

## Import extensions from file
To import and install extensions from a extensions file, perform the following on your machine:
```bash
source <file_with_extensions>
```

