# ArtMitra User Journey

## Seller Journey

```mermaid
flowchart TD
    subgraph "Seller Journey"
        A1["Registration Phase"]
        A2["Complete Profile"] --> A3["Feeling: Excited to start selling"]
        A3 --> A4["Pain: Form complexity"]
        A4 --> B1["Product Listing Phase"]
        B2["List Product"] --> B3["Feeling: Hopeful for approval"]
        B3 --> B4["Pain: Product approval delay"]
        B4 --> C1["Tutorial Upload Phase"]
        C2["Upload Tutorial"] --> C3["Feeling: Proud of craftsmanship"]
        C3 --> C4["Pain: Video upload issues"]
        C4 --> D1["Order Management Phase"]
        D2["Manage Orders"] --> D3["Feeling: Busy managing orders"]
        D3 --> D4["Pain: Complex order tracking"]
    end

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
