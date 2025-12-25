

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

Check out my [status page](https://status.vedgupta.in/) for updates on my projects and availability.


<img height="70px" src="https://skillicons.dev/icons?i=react,nextjs,nodejs,javascript,typescript,python,bash,flask,git,github,graphql,aws,gcp,cloudflare,docker,firebase,githubactions,go,mongodb,mysql,planetscale,prisma,tailwind,vscode" />
