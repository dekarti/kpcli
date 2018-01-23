What is kpcli?
--------------

`kpcli` - command line interface to work with KeePass 1.x or 2.x database files.

How to use this image?
----------------------
Running the following command will bring you to `kpcli` interactive shell:

```
$ docker run -it dekarti/kpcli:latest
```

Mounting volume with `.kdb[x]` files:

```
$ docker run -it /path/to/kdb/files:/opt/data dekarti/kpcli:latest
```

Using in non-interactive mode:
```
$ docker run -it dekarti/kpcli:latest sh
# kpcli --help
```


Notes
-----

This image:
- is built on top of Alpine Linux v.3.6 Docker image 
- weights around 40MB

References
----------

1. [kpcli - A command line interface to KeePass database files](http://kpcli.sourceforge.net/)
2. [Alpine Linux](https://alpinelinux.org)
