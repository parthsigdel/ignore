Instantly create a .gitignore file for your project through your command line. 

## Installation:

### macOS / Linux
```
curl -fsSL https://sh.parthsigdel.com/ignore | sh
```

### Windows
```
irm https://sh.parthsigdel.com/ignore.ps1 | iex
```

## Usage
Type `ignore <project-type>` to create a .gitignore file for your project. 

Example: `ignore rust`

This will create a .gitignore file for a rust project. 

Incase, you already have a .gitignore file, recommended patterns will be appended, 
and duplicates will not be added to your existing .gitignore file. 

See `ignore --all` to see the list of supported projects.
