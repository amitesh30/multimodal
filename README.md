``` mermaid
flowchart TD
    A[Input Image] --> B[Conv2d Layer]
    B --> B1["Conv2d (3, 64, '7x7')"]
    B1 --> C[ReLU Activation]
    C --> D[MaxPool Layer]
    D --> E[ResNet Block 1]
    E --> F[ResNet Block 2]
    F --> G[ResNet Block 3]
    G --> H[ResNet Block 4]
    H --> I[YOLO Head]
    I --> J[Predicted Bounding Boxes]
```
