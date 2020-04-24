# backup-scripts

## General interface

### Export
Create a tar.gz archive out of data and configuration
```
$ ./[software_name]-export
```

### Import
Import backed up data into the system
```
$ ./[software_name]-import [software_name].tar.gz
```

### Restore
Replace current installation data and configuration with one from the backup
```
$ ./[software_name]-restore [software_name].tar.gz
```

### Check
Check backup integrity
```
$ ./[software_name]-check [software_name].tar.gz
```

## Todo features

* optionally encrypt archives
