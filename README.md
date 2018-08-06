# Docker alpine knife

Docker image helper for different CLI command's based on Alpine OS.

## Git

```bash
docker run --rm -v $(pwd):/do ctgec/knife git pull
```

## htpasswd

```bash
docker run --rm -v $(pwd):/do ctgec/knife htpasswd -Bbn USER PASS
```

... will print out *`USER:bcrypt-encrypted-PASS`*

## what else do we need? :=)
