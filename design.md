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
int1["Interface 1 fa:fa-twitter"]
int2["Interface 2"]
int3["Interface 3"]
subgraph Session1
int1 -->int2
int2 --> int3
end
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg3ODI4MDcwMSw1MjUzMjQ3ODVdfQ==
-->