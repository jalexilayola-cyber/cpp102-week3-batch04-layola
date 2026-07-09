flowchart TD
    A(["Start"]) --> B[\"Input lab scores"\]
    B --> C[\"Input attendance"\]
    C --> D[\"Input quiz scores"\]
    D --> E["laboratory standing = (lab work * 40%) + (attendace * 20%) + (quiz scores * 40%)"]
    E --> F[\"Display laboratory standing"\]
    F --> G(["End"])