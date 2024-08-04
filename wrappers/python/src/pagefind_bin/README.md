<!-- Note: this is a template file that is used for both pagefind_bin and pagefind_python_extended. All occurrences of `pagefind_bin` will be replaced with the actual package name -->
# `pagefind_bin`
A python wrapper for the pagefind binary.

## Usage

```py
from pagefind_bin import get_executable
print(get_executable()) # yields absolute path to the binary
```
```sh
python3 -m pagefind_bin --help
```