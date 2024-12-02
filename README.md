# GitHub File Manager

A simple and efficient system for managing GitHub files with proper encoding and handling.

## Features

- Proper base64 encoding for file content
- Error handling
- Simple API

## Usage

```python
from filemanager import FileManager

# Initialize manager
manager = FileManager('owner', 'repo')

# Prepare file content
file_data = manager.create_file_data(
    path='example.txt',
    content='Hello, World!',
    message='Add example file'
)
```