


## Note:

if you're here, you're probably better off looking at:

- the `./hosts/rpizero2` dir in `colemickens/nixcfg`
- the 'crosspkgs' branch on `colemickens/nixpkgs`

The former defines a nixos system for a Raspberry Pi Zero W.

The latter is a branch named `crosspkgs`, rebased on top of my custom `cmpkgs` branch, that includes extra fixes for cross-compiling. I mostly keep these separate from `cmpkgs` to avoid large rebuilds on my normal hosts.
