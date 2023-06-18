### Hi there 👋

```python
import time

message = "Hello, World!"

while True:
    print(message, end='\r')
    time.sleep(0.5)
    print(" " * len(message), end='\r')
    time.sleep(0.5)

