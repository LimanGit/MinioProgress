# MinioProgress

A progressbar for python minio.

You can import this lib and put the progress class into any
minio operation and it will show a progressbar.

For more info for the use cases please read the official minio documents for python.

# Install
```bash
pip install MinioProgress
```

# Example

```python
# Import
from MinioProgress.Progress import Progress

# Example with fput_object
client.fput_object(
    "my-bucket", "my-object", "my-filename",
    progress=Progress() # Pass the Progress class
)
```

# TODO

Muktiple progressbar design.
