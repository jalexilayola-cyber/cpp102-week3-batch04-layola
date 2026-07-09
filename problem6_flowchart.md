flowchart TD
    A(["Start"]) --> B[\"Input budget"\]
    B --> C[\"Input days"\]
    C --> D[\"Input transportation"\]
    D --> E["monthly budget = (budget * days) + (transportation * days)"]
    E --> F[\"Display monthly budget"\]
    F --> G(["End"])