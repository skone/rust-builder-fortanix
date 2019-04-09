# rust-builder-fortenix
A container for building rust code targeting the Fortenix EDP.
This is useful if you don't want to install all of the fortenix libraries,
or if you're developing on a non-linux system e.g. MacOs

To use this image install the cargo docker sub command

```bash
cargo install cargo-docker
```
Then in the root of your project run

```bash
cargo docker --image=sskone/rust-builder-fortenix --output=build/fortenix-target
```
