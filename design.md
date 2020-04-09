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

## Front-end framework

In general, a **front-end framework** is a scaffold for building the front end. It usually includes some way to structure files
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzkwOTIyNzcyLDc1MDc0MDE1MCwzMjM1MT
A0NTYsNTI1MzI0Nzg1XX0=
-->