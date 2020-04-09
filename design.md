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

API - Application programming interface is a set of definitions and protocols for building and integrating application software. 
**GraphQL** is an open-source data query and manipulation language for [APIs](https://en.wikipedia.org/wiki/Application_programming_interface "Application programming interface"), and a runtime for fulfilling queries with existing data.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxNTg0MTYzMywtNjAzMzUzMjg2LC0xND
E4NTg1OTIxLC0xNTY5ODIxNDE0LC0xODIyNzQyMDM2LDc1MDc0
MDE1MCwzMjM1MTA0NTYsNTI1MzI0Nzg1XX0=
-->