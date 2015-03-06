# Mesos dependencies pulled out of Mesos

Useful if you have other software which needs the same common dependencies such
as mesos modules, or your own out of tree scheduler.

## Usage

```
./make_env [directory]
```

make_env will output values to use for several mesos configure flags.
 --with-glog=
 --with