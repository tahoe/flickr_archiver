# flickr_archiver
Archive your flickr account periodically

Follow instructions at https://github.com/alexis-mignon/python-flickr-api/wiki/Tutorial
to set up your authentication file in ~/.flickr_archiver/auth.txt

Also set up your config in ~/.flickr_archiver/config.yaml as such:

Optionally, you may provide a path to the config.yaml (or other name.yaml)
with the -f option

```yaml
api_sec: "your security key"
api_key: "your api key"
base_folder: "folder where you want to have us store your files"
min_upload_hours: "number of hours to go back based on upload time"
auth_file: "path to your auth.txt file"
```
