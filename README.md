# marketing-redirects

Add redirection mapping in the format:
```
from-URL<space>to-URL<semi-colon>
```
The urls starts from the "/" after .com and ends at the last "/" in the complete URL.

Example:

Let's say we have 2 URLs

https://www.aasaanjobs.com/org/coverfox/db841055-4a8f-434f-ae62-a7caa2d12078/

and

https://www.aasaanjobs.com/org/coverfox-pvt-ltd/db841055-4a8f-434f-ae62-a7caa2d1asdasd/

and we want all the traffic to redirect to the second URL.

The contents of our map file in that case will be:

```
/org/coverfox/db841055-4a8f-434f-ae62-a7caa2d12078/ /org/coverfox-pvt-ltd/db841055-4a8f-434f-ae62-a7caa2d1asdasd/;
```
