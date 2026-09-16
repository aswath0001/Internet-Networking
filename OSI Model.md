# OSI Model

## What is OSI Model?

The OSI (Open Systems Interconnection) Model is a conceptual framework created by the International Organization for Standardization (ISO) to describe how data is transmitted across a network using a structured seven-layer architecture.

## Layers of OSI Model 

OSI model uses a seven steps for transmitting or sharing data or files between two computers. Those layers are ,

```mermaid
graph TD
    L7["Layer 7: Application"] --> L6["Layer 6: Presentation"]
    L6 --> L5["Layer 5: Session"]
    L5 --> L4["Layer 4: Transport"]
    L4 --> L3["Layer 3: Network"]
    L3 --> L2["Layer 2: Data Link"]
    L2 --> L1["Layer 1: Physical"]
```  

### Application Layer 

Application layer refers the software applications we use like Whatsapp, Instagaram etc..

### Presentation Layer 

Presentation Layer receives the data from the application layer and converts it into meachine representable code
 