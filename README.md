# security

`backup.sh`
```sh
#!/bin/bash

backup_dir="$HOME/Documentos"

DATE_TIME=$(date +"%Y-%m-%d_%H:%M:%S")
zip_file="$HOME/Escritorio/docs-$DATE_TIME.zip"

zip -r "$zip_file" "$backup_dir"
```

```sh
chmod +x backup.sh
```
