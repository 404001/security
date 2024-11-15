# security

`backup.sh`
```sh
#!/bin/bash

backup_dir="$HOME/Documents"

DATE_TIME=$(date +"%Y-%m-%d_%H-%M-%S")
zip_file="$HOME/Desktop/docs-$DATE_TIME.zip"

zip -r "$zip_file" "$backup_dir"
```
