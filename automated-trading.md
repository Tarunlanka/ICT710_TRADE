# Automated Trading Wizard

## Usability problem
The simulated baseline reports 60% completion, 118 seconds mean time, and six errors for automated trading. Rule-based setup can be difficult when conditions, triggers, and actions are unclear.

## Proposed five-step wizard
1. **Choose asset:** Identify the asset and trading direction.
2. **Set trigger:** Define the price or condition that starts the rule.
3. **Set action:** Specify what should happen when the trigger is met.
4. **Set limits:** Review quantity, spending limits, expiry, and risk controls.
5. **Review and activate:** Show a plain-language summary and require explicit confirmation.

## Plain-language rule summary
Before activation, summarise the asset, trigger condition, action, limits, and what happens if the condition is not met. Let users edit any step from the review screen.

## Safeguards
- Keep the rule inactive until explicit confirmation.
- Show the rule status and provide pause, edit, and cancel controls.
- Explain that automation may not execute exactly as expected and that market conditions can change.
- Avoid implying that a rule guarantees profit or a specific execution price.

## Evaluation plan
Observe whether users can correctly describe the rule they created, complete setup without help, identify how to pause it, and understand the risks. The re-test remains planned until it is actually conducted.
