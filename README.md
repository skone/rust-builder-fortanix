# rust-builder-fortanix
A container for building rust code targeting the Fortanix EDP.
This is useful if you don't want to install all of the fortanix libraries,
or if you're developing on a non-linux system e.g. MacOs

To Use this image execute the following docker command in the root of your directory

```bash
docker run -it -v "$(pwd):/source"  -w /source --rm sskone/rust-builder-fortenix cargo build
```
