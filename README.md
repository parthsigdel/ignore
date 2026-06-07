Instantly create a .gitignore file for your project through your command line. 

#### Installation:

```
go install github.com/CoderParth/ignore@latest
```

Then make sure your Go bin directory is on your PATH. Add this to your shell config (~/.bashrc, ~/.zshrc, etc.):
```bash
export PATH=$PATH:$(go env GOPATH)/bin
```

Reload it:
```bash
source ~/.zshrc  # or ~/.bashrc
```

#### Usage
Type `ignore <project-type>` to create a .gitignore file for your project. 

Example: `ignore rust`

This will create a .gitignore file for a rust project. 

Incase, you already have a .gitignore file, recommended patterns will be appended, 
and duplicates will not be added to your existing .gitignore file. 

See `ignore --all` to see the list of supported projects.
