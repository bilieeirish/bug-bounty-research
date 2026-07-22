# Smart Contract Audit Checklist

## Access Control
- [ ] Owner-only functions
- [ ] Role-based access
- [ ] Reentrancy guards
- [ ] Timelock mechanisms

## Financial Logic
- [ ] Price oracle manipulation
- [ ] Flash loan attacks
- [ ] Slippage tolerance
- [ ] Fee calculations

## Token Handling
- [ ] ERC20 compliance
- [ ] Transfer hooks
- [ ] Approval race conditions
- [ ] Fee-on-transfer tokens

## External Calls
- [ ] Low-level calls
- [ ] Return value checks
- [ ] Gas limit considerations
- [ ] Delegatecall safety

## Edge Cases
- [ ] Zero address checks
- [ ] Overflow/underflow
- [ ] Division by zero
- [ ] Precision loss
