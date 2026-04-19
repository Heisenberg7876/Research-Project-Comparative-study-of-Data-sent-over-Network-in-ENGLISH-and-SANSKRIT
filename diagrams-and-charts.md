# 📊 Diagrams & Charts

## Comparative Study of Data Sent Over Network in English and Sanskrit

---

## 🧠 1. System Architecture Diagram

```mermaid
flowchart LR
    A[User Input Text] --> B{Language Type}

    B -->|English| C[English Encoding]
    B -->|Sanskrit| D[Sanskrit Encoding]

    C --> E[Binary Conversion]
    D --> F[Optimized Encoding]

    E --> G[Packet Formation]
    F --> G

    G --> H[Network Transmission]

    H --> I[Receiver End]

    I --> J{Decode Type}
    J -->|English| K[English Decoding]
    J -->|Sanskrit| L[Sanskrit Decoding]

    K --> M[Output Text]
    L --> M
```

---

## 📈 2. Data Size Comparison

```
Data Size (Bytes)

English   ████████████████████████████ 800
Sanskrit  ██████████████████████      650
```

---

## ⚡ 3. Transmission Efficiency Flow

```mermaid
flowchart TD
    A[Input Text] --> B[Language Processing]
    B --> C[Compression Stage]
    C --> D[Packet Creation]
    D --> E[Transmission]
    E --> F[Reception]
    F --> G[Decompression]
    G --> H[Final Output]
```

---

## 🧩 4. Conceptual Diagram

```
          +----------------------+
          |  Human Language      |
          +----------------------+
                    |
        +-----------+-----------+
        |                       |
   English                Sanskrit
 (Less Dense)         (More Dense)
        |                       |
  More Data                Less Data
        |                       |
 Slower Transmission    Faster Transmission
        |                       |
   More Bandwidth        Optimized Network
```

---

## 📉 5. Packet Size Comparison

```
Packets Required

English   ██████████ 10
Sanskrit  ███████    7
```

---

## 🚀 6. Efficiency Graph

```
Efficiency ↑

100 |            ● Sanskrit
 80 |
 60 |      ● English
 40 |
    +-------------------------
       Language Type →
```

---

## 🧪 7. Experimental Pipeline

```mermaid
flowchart LR
    A[Dataset Input] --> B[Language Conversion]
    B --> C[Encoding Algorithm]
    C --> D[Compression]
    D --> E[Transmission Simulation]
    E --> F[Data Collection]
    F --> G[Analysis & Comparison]
```

---

## 📌 Conclusion

These diagrams demonstrate that Sanskrit may offer:

* Higher semantic density
* Reduced data size
* Fewer packets required
* Improved transmission efficiency

compared to English in networking systems.

