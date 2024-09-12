# Homebrew

### General

```bash
# Install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
# Update brew & all formulae
brew update
```

```bash
# Upgrade all casks & formulae
brew upgrade
```

```bash
# List installed casks & formulae
brew list
```

### Formulae

```bash
# Install a formula
brew install dotnet
```

```bash
# Uninstall a formula
brew uninstall dotnet
```

```bash
# Upgrade a formula
brew upgrade dotnet
```

```bash
# List installed formulae only
brew list --formula
```

```bash
# List all versions of a formula
brew list --versions dotnet
```

```bash
# Change used formula version
brew switch dotnet 8.0.4
```

```bash
# Show information about a formula installation
brew info dotnet
```

```bash
# Search formulae by name and casks by token
brew search dotnet
```

### Casks

```bash
# Install a cask, e.g. Visual Studio Code
brew install --cask visual-studio-code
```

```bash
# Uninstall a cask
brew uninstall --cask visual-studio-code
```

```bash
# List installed casks only
brew list --cask
```