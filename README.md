<div align="center">
  <img src="https://github.com/AllanDza/Vita_Vue/blob/main/Vanilla-1s-286px.gif" alt="Animated GIF">
</div>
<div>
  <h1> Abstract </h1>
  <p>Our project introduces an IoMT device designed for efficient monitoring of diabetic patients' vital signs. Using near-infrared (NIR) technology, the device measures blood glucose, blood pressure, heart pulse, and oxygen levels non-invasively, ensuring patient comfort. Data is transmitted in real-time to the cloud, accessible via a mobile app for both patients and doctors. Advanced algorithms process data to provide personalized insights, enabling proactive management of diabetic conditions. This integrated solution offers convenience, remote accessibility, and improved patient outcomes in diabetic care.</p>

graph TD;
    A[Start] --> B[Initiate Measurement];
    B --> C[Activate NIR Sensors];
    C --> D[Measure Blood Glucose];
    C --> E[Measure Blood Pressure];
    C --> F[Measure Heart Pulse];
    C --> G[Measure Oxygen Levels];
    D --> H{Valid Reading?};
    E --> H;
    F --> H;
    G --> H;
    H -->|Yes| I[Transmit Data to Cloud];
    H -->|No| B;
    I --> J[Cloud Data Processing];
    J --> K[Generate Insights];
    K --> L[Display in Mobile App];
    L --> M{More Measurements?};
    M -->|Yes| B;
    M -->|No| N[End];
<details>
  <summary>Process Overview</summary>
  graph TD;
    A[Start] --> B[Initiate Measurement];
    B --> C[Activate NIR Sensors];
    C --> D[Measure Blood Glucose];
    C --> E[Measure Blood Pressure];
    C --> F[Measure Heart Pulse];
    C --> G[Measure Oxygen Levels];
    D --> H{Valid Reading?};
    E --> H;
    F --> H;
    G --> H;
    H -->|Yes| I[Transmit Data to Cloud];
    H -->|No| B;
    I --> J[Cloud Data Processing];
    J --> K[Generate Insights];
    K --> L[Display in Mobile App];
    L --> M{More Measurements?};
    M -->|Yes| B;
    M -->|No| N[End];

</details>
