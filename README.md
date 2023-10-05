# nix-demonstration
### Nix demonstration for school project
---
## Whats this?
This is an example Nix package that was used in my school presentation. Specifically, it was used to analyze the anatomy of a nix package, and to demonstrate a nix build in action.

This is just the `hello` package from nixpkgs stored in a repository.

## How to build
You may build the package from the following command:
`nix-build -E 'with import <nixpkgs> {}; callPackage ./default.nix {}'`

## Credits
Special thanks to the nixpkgs contributors, and credits to go Eelco Dolstra for building the original package.
