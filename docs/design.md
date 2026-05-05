# Design: Add to Cart

*Linked issues: #1, #2*

## Sketch

```
[Apple - $2]   [Add to Cart]
[Bread - $4]   [Add to Cart]

   Cart: 2 items
```


## Data flow

- **Input:** user clicks the Add to Cart button on a product
- **Process:** the selected product is added to a cart array, and the cart total is recalculated
- **Output:** the cart count on screen updates to show the new number of items

## Design decisions

- Cart is stored in a JavaScript array because it is simple and enough for this version
- Each product has its own Add to Cart button so users can add items individually
- Clicking Add to Cart adds 1 item each time; quantity editing is out of scope for now
