flowchart TD
    A[Extract Data from Oracle] --> B[Transform Data]
    B --> C1[Data Cleaning]
    B --> C2[Data Formatting]
    B --> C3[Data Aggregation]
    C1 --> D[Load Transformed Data into Staging]
    C2 --> D
    C3 --> D
    D --> E[Final Data Load into SAP]
