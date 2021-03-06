## pouch rmi

Remove one or more images by reference

### Synopsis

Remove one or more images by reference

```
pouch rmi image  [flags]
```

### Examples

```
$ pouch rmi docker.io/library/busybox:latest
docker.io/library/busybox:latest
```

### Options

```
  -f, --force   if image is being used, remove image and all associated resources
  -h, --help    help for rmi
```

### Options inherited from parent commands

```
  -H, --host string        Specify connecting address of Pouch CLI (default "unix:///var/run/pouchd.sock")
      --tlscacert string   Specify CA file of TLS
      --tlscert string     Specify cert file of TLS
      --tlskey string      Specify key file of TLS
      --tlsverify          Use TLS and verify remote
```

### SEE ALSO

* [pouch](pouch.md)	 - An efficient container engine

