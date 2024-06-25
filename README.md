
## Buyer Journey

```mermaid
flowchart TD
    subgraph "Buyer Journey"
        E1["Registration Phase"]
        E2["Browse Products"] --> E3["Feeling: Curious about products"]
        E3 --> E4["Pain: Sign-up friction"]
        E4 --> F1["Shopping Phase"]
        F2["Add to Cart"] --> F3["Feeling: Excited to purchase"]
        F3 --> F4["Pain: Difficulty in product filtering"]
        F4 --> G1["Checkout Phase"]
        G2["Checkout"] --> G3["Feeling: Happy with purchase"]
        G3 --> G4["Pain: Payment gateway issues"]
        G4 --> H1["Post-Purchase Phase"]
        H2["Receive Order"] --> H3["Feeling: Eager to receive product"]
        H3 --> H4["Pain: Delivery delays"]
        H4 --> I1["Feedback Phase"]
        I2["Review"] --> I3["Feeling: Satisfied with product"]
        I3 --> I4["Pain: Review submission problems"]
    end
