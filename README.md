Install in ~/Library/Application Support/Code/User (on Mac)

Other platforms see https://stackoverflow.com/questions/35368889/how-to-export-settings-of-visual-studio-code

Install the extensions with

    sh ./install-extensions.sh

Update the extensions list with
```bash
code --list-extensions | xargs -L 1 echo code --install-extension > install-extensions.sh
```

License: [MIT](LICENSE) where copyrightable. No warranty.
