# OS/161 toolchain with Homebrew

The following instructions will add this repository to your Homebrew and build all
the tools form source automatically:
```sh
brew tap Ivan-Velickovic/os161-homebrew https://github.com/Ivan-Velickovic/os161-homebrew
brew install bmake os161-binutils os161-gcc os161-gdb sys161
```

All source files are from the UNSW COMP3231 website.

# Credit

Thanks to Nikhil Benesch and Jason Codd for the original formulae, which I have cleaned up
and fixed slightly.
