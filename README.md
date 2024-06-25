
```mermaid
journey
    title User Journey for ArtMitra

    %% Seller Journey
    section Seller
    phase "Registration" {
        action "Complete Profile" : smiling
        feeling "Excited to start selling" : happy
        pain "Form complexity" : neutral
    }
    phase "Product Listing" {
        action "List Product" : thinking
        feeling "Hopeful for approval" : hopeful
        pain "Product approval delay" : worried
    }
    phase "Tutorial Upload" {
        action "Upload Tutorial" : writing
        feeling "Proud of craftsmanship" : proud
        pain "Video upload issues" : frustrated
    }
    phase "Order Management" {
        action "Manage Orders" : busy
        feeling "Busy managing orders" : stressed
        pain "Complex order tracking" : tired
    }

    %% Buyer Journey
    section Buyer
    phase "Registration" {
        action "Browse Products" : browsing
        feeling "Curious about products" : curious
        pain "Sign-up friction" : irritated
    }
    phase "Shopping" {
        action "Add to Cart" : shopping_cart
        feeling "Excited to purchase" : excited
        pain "Difficulty in product filtering" : annoyed
    }
    phase "Checkout" {
        action "Checkout" : checkout
        feeling "Happy with purchase" : happy
        pain "Payment gateway issues" : frustrated
    }
    phase "Post-Purchase" {
        action "Receive Order" : delivery
        feeling "Eager to receive product" : eager
        pain "Delivery delays" : upset
    }
    phase "Feedback" {
        action "Review" : feedback
        feeling "Satisfied with product" : satisfied
        pain "Review submission problems" : annoyed
    }

