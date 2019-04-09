# rust-builder-fortenix
A container for building rust code targeting the Fortenix EDP.
This is useful if you don't want to install all of the fortenix libraries,
or if you're developing on a non-linux system e.g. MacOs

To Use this image execute the following docker command in the root of your directory

```bash
docker run -it -v "$(pwd):/source"  -w /source --rm sskone/rust-builder-fortenix cargo build
```
