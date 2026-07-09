flowchart TD
    A(["Start"]) --> B["Inputnet"]
    B --> C{"net &gt; 0"}
    C -- Yes --> D["Display Deposit"]
    C -- No --> E{"net &lt; 0"}
    E -- Yes --> F["Display Withrawal"]
    E -- No --> G["Display No Change"]
    D --> H(["End"])
    F --> H
    G --> H