```
flowchart ID
 A(["Inicio"])
 A --> B{"Faça uma Escolha"}
 B --> C["OP1"]
 B --> D["OP2"]
 B --> E["OP3"]
 ```
```
```mermaid
graph TD;
 A[Inicio] --> B{Nota >6};
 B --> [SIM] C[Aprovado];
 B --> [Não] D[Reprovado];
```
