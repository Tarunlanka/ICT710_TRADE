# Buy/Sell and Order Confirmation

## Usability problem
The simulated baseline reports 80% completion for purchase (72 seconds, three errors) and sell (80%, 64 seconds, two errors). Trading actions need clear direction and a review of important order details before commitment.

## Proposed interaction
1. Open an asset.
2. Select a consistently placed **Buy** or **Sell** action.
3. Enter quantity or amount.
4. Review order type, quantity, estimated price, fees, and total.
5. Confirm the order explicitly.
6. Display order status and a receipt/reference.

## Design principles
- Keep Buy and Sell actions visually distinct and consistently located.
- Do not rely on colour alone to communicate action meaning.
- Make the selected action visible throughout the flow.
- Show relevant costs and order details before the final action.
- Provide clear feedback after submission and distinguish submitted, pending, rejected, and completed states.

## Evaluation questions
- Can users identify whether they are buying or selling?
- Can users explain the order total before confirmation?
- Do users notice and understand fees?
- Can users recover from an incorrect quantity without restarting?
