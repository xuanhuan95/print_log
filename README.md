# Print Logger

Python print with strict structure

```bash
time|trace_id|PID|thread_info|level|class_method_line|message
```
thread_info = name-native_id-identity_id

## Install

```bash
pip install print-logger
```

## Usage

```python
from print_logger import print_log, ERROR, INFO, WARNING

# info level
print_log('message info', INFO)
# error level
print_log({'message': 'error'}, ERROR)
# warning level
print_log('message warning', WARNING)
# custom level
print_log('message custom', 'CUSTOM')
```
