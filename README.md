# ccs-push

Used by ccs to stage files for OODS and DBB services

usage: ccs-push -h hostname -c camera -s subdir -f filename [-d]

where:
```
-h hostname it transfer to
-c auxtel or comcam
-s subdirectory to place file (a, a/b, a/b/c, etc.)
-f filename
-d (optional) also link this to the data backbone buffer manager directory
```

