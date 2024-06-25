
### Explanation of Flowchart Nodes and Connections

- **Nodes**: Represent different phases, actions, feelings, and pain points.
  - E.g., `A1`, `A2` etc., denote actions or feelings.
  - Use labels to provide context like `"Feeling: Excited to start selling"` or `"Pain: Form complexity"`.
- **Connections (`-->`)**: Indicate the flow from one step to the next.

### Steps to Use in GitHub

1. **Create or Edit a Markdown File**: Create a `README.md` or another `.md` file in your GitHub repository.
2. **Insert the Mermaid Code**: Use the provided code snippets for the seller and buyer journeys.
3. **Save and Commit**: Save the changes and commit them to your repository.
4. **View on GitHub**: GitHub will render the diagram when you view the Markdown file in the repository.

### Complete Markdown Example

```markdown
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
