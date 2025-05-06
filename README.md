# Reflections

A utility to detect reflection vulnerabilities in URLs (query parameters and URL paths).

## Features

### Query Parameter Reflection Check
Checks for reflected parameters in URLs.

```bash
python3 query_reflection.py urls.txt --threads 2

### URL Path Reflection Check
Verifies reflection in URL path segments.


python3 path_reflection.py urls.txt --threads 2

### Parameters
urls.txt : Text file containing URLs to test (one per line)

--threads : Number of concurrent threads to use (default: 2)

### Usage
Prepare your URLs in urls.txt

Run either checker script with desired thread count:

  
python3 query_reflection.py your_urls.txt --threads 5

Note Replace urls.txt with your actual file path. Adjust thread count based on your system capabilities.


This includes:
- Clear separation between different checks
- Code blocks with proper syntax highlighting
- Parameter explanations
- Usage instructions
- Important note about file paths and thread counts

You might want to add these additional sections:
- Prerequisites (Python version, required libraries)
- Installation instructions
- Output format explanation
- Example results
- Contributing guidelines

Credits
Originally developed by xss0r. Thanks for creating and sharing this tool!
