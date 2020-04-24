# backup-scripts

## General interface

Create a tar.gz archive out of data and configuration
```
$ ./[software_name]-backup
```

Replace current installation data and configuration with one from the backup
```
$ ./[software_name]-restore [software_name].tar.gz
```

Import is like restore, but doesn't replace, just adds backed up entries
```
$ ./[software_name]-import [software_name].tar.gz
```

