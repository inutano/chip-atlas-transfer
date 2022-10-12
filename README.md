# chip-atlas-transfer

For data transfer via MinIO client

## Usage

```
$ ./chip-atlas-transfer
chip-atlas-transfer: 0.1.0
Usage:
  chip-atlas-transfer <directory>
  chip-atlas-transfer help
  chip-atlas-transfer clean
```

## Tips

- This util uses `mc mirror` command with the options `--remove` and `--overwrite`, which removes remote unrelated objects and overwrite the remote files.
