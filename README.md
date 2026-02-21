# Setup
1) Install mise to get ruby, https://mise.jdx.dev/ 
2) Add mise and the file where this script is to your .zshrc
```bash
   eval "$(/opt/homebrew/bin/mise activate)"
   export PATH="$HOME/Development/utils:$PATH"
```
3) Because `#!/usr/bin/env ruby` is on the first line, we don’t need the .rb suffix for the file name and bash knows it’s executable

Used `brew install glow gum` to make this README better

To read this README.md nicely, run `cat README.md | glow`