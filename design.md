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

## Front-end app

In general, the **front end** is the presentation layer of our application. It’s often described as all the stuff the user sees, but more generally, it’s any code that’s responsible for efficiently displaying data to the user. So, the front end includes building intuitive and pleasant interfaces, as well as efficiently storing, presenting, and updating data received from the back end or API. 
The user interface is implemented using React.js.
**React.js** is an **open source JavaScript library** used for front end development, which was developed by Facebook. Its component-based library allows us to build high-quality user-interfaces for web apps.

## API

An _**a**pplication  **p**rogram  **i**nterface_ (**API**) is a set of [routines](https://www.webopedia.com/TERM/R/routine.html), [protocols](https://www.webopedia.com/TERM/P/protocol.html), and tools for building [software applications](https://www.webopedia.com/TERM/A/application.html).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg1MzAxMzMwLC0xNDE4NTg1OTIxLC0xNT
Y5ODIxNDE0LC0xODIyNzQyMDM2LDc1MDc0MDE1MCwzMjM1MTA0
NTYsNTI1MzI0Nzg1XX0=
-->