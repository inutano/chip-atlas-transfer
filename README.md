# chip-atlas-transfer

For data transfer via MinIO client

## Usage

```
$ ./chip-atlas-transfer
chip-atlas-transfer: 0.1.0
Usage:
  chip-atlas-transfer <source_directory> <target_path>
  chip-atlas-transfer help
  chip-atlas-transfer clean
```

```
$ chip-atlas-transfer ~/data/tmp/hg19/allPeaks_light hg19/allPeaks_light_2022
```

## Tips

- This util uses `mc mirror` command with the options `--remove` and `--overwrite`, which removes remote unrelated objects and overwrite the remote files.
