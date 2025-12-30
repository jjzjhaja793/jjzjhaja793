

```python
#!/usr/bin/env python3

__author__	= "Ved Prakash Gupta"
__copyright__   = f"Copyright (c) 2002 {__author__}"
__license__ 	= "Private Domain"
__version__	= "23.7.0"

import subprocess
res = subprocess.run(["python3" , "-c" , "print('Feel the Code not Write it')"],
		capture_output=True, text=True
		)

print("stdout:", res.stdout)	# Output
if res.stderr != "" : print("stderr:", res.stderr)	# Error

```
