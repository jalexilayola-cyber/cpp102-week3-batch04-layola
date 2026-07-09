flowchart TD
    A(["Start"]) --> B["Input gwa"]
    B --> C{"gwa &gt;= 90"}
    C -- Yes --> D["Display Eligible for Scholarship"]
    C -- No --> E["Display Not Eligible for Scholarship"]
    D --> F(["End"])
    E --> F