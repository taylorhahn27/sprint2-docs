# Functional Roles Software Implementation
<sub><sup>"Functional Roles" is an abstract model of the functional roles present within the system<br> "Implementation" is demonstrating specifc types of software used to implement those functional roles within JCB</sup></sub>
---

```mermaid
graph BT
subgraph Implementation
a[HKS SQL<br> Data Warehouse Server] --> b[Apollo Server]
b --> c[Serverless Platform on Azure]
c --> d[Client on Browser]
end
subgraph Functional Roles
e(SQL<br> Data Warehouse Server) --> f(Generic Graph<br> Server)
f --> g(Serverless)
g --> h("Generic Browser (Client)")
end
```  