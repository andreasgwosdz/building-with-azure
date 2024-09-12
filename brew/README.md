# Homebrew Cheatsheet

[Go to Website](https://brew.sh/)

Install Homebrew
```bash
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Update Homebrew & fetch latest formulae

```bash
$ brew update
```

Install a formula, e.g. dotnet
```bash
$ brew install dotnet
```

Upgrade outdated formula/casks
```bash
$ brew upgrade
```

Uninstall a formula, e.g. dotnet
```bash
$ brew uninstall dotnet
```

Search formulae by name and casks by token
```bash
$ brew search dotnet
==> Formulae
dotnet ✔                        dotnet@6                        dotter                          dotbot

==> Casks
dotnet                          dotnet-sdk                      dotnet-sdk@preview              dotnet@preview
```

List formulae and/or casks in long format
```bash
$ brew ls -l
==> Formulae
total 0
drwxr-xr-x@ 3 andreas  admin  96 Sep 12 09:04 azure-cli
drwxr-xr-x@ 3 andreas  admin  96 Sep 12 09:04 python@3.11
drwxr-xr-x  3 andreas  admin  96 Sep 12 09:03 terraform
...

==> Casks
total 0
drwxr-xr-x  4 andreas  admin  128 Jul 17 22:36 iterm2
drwxr-xr-x  4 andreas  admin  128 Jul 17 21:52 obsidian
drwxr-xr-x  4 andreas  admin  128 Jul 17 22:48 visual-studio-code
...
```