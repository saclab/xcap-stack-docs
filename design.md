# Design


```mermaid
graph TB
frontend["Frontend APP"]
api["API"]
core["XCAP.Core Daemon"]

frontend --> api
api --> core
core --> Sessions
```
```mermaid
graph LR
int1["Interface 1"]
int2["Interface 2"]
int3["Interface 3"]
subgraph Session 1
int1 -->int2
int2 --> int3
end
```

```mermaid
graph LR
int1["Module 1"]
int2["Module 2"]
int3["Module 3"]
subgraph Interface 1
int1 -->int2
int2 --> int3
end
```
This framework is built of multiple interfaces for each individual program in the crystallography process. Each interface is built of individual modules which are further comprised of sets of scripts and functions. The interfaces allow a set of i/p files and generates the output to the next interface in the pipeline.

<!--stackedit_data:
eyJoaXN0b3J5IjpbNTI4MTI3ODA4LDMyMzUxMDQ1Niw1MjUzMj
Q3ODVdfQ==
-->