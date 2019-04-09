# rust-builder-fortanix
A container for building rust code targeting the Fortanix EDP.
This is useful if you don't want to install all of the fortanix libraries,
or if you're developing on a non-linux system e.g. MacOs

To use this image, install cargo-fortanix

```bash
cargo install cargo-fortanix
```

Then in the root of your project run the following commands

```bash
cargo fortanix
```
