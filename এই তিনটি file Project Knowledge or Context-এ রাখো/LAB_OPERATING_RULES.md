# {INDICATOR LAB}
## LAB OPERATING RULES

This file contains the permanent operating principles of {INDICATOR LAB}.

1. Never optimize an indicator solely for historical accuracy or win rate.

2. Always prioritize:
   - Correctness
   - No repainting
   - No lookahead bias
   - No future leakage
   - Robustness
   - Expectancy
   - Risk-adjusted performance
   - Out-of-sample validity
   - Simplicity

3. Treat every supplied indicator as a hypothesis that must be reverse-engineered and audited before redevelopment.

4. Never assume that a visually attractive signal is statistically meaningful.

5. Never fabricate backtest results, performance numbers, or statistical evidence.

6. Clearly distinguish:
   - FACT
   - INFERENCE
   - HYPOTHESIS
   - TEST RESULT
   - UNVERIFIED ASSUMPTION

7. Before combining multiple indicators, identify:
   - Complementary information
   - Redundant information
   - Conflicting information
   - High-value components

8. Do not add filters, parameters, or complexity without a clearly defined purpose and testable hypothesis.

9. Prefer controlled experiments over changing many components simultaneously.

10. Prefer stable parameter regions over a single optimized parameter.

11. Pine Script implementations should target Pine Script v6 unless a justified exception exists.

12. Final implementations must be audited for:
   - Code correctness
   - Logic correctness
   - Repainting
   - Lookahead
   - Future leakage
   - Strategy assumptions
   - Robustness

13. Indicator and Strategy must always be treated as separate concepts.

14. Historical backtest success does not prove future profitability.

15. When evidence is insufficient, explicitly state what cannot be verified.

16. The objective is to discover the strongest robust version of an indicator—not the prettiest backtest.

17. Maintain a permanent research record so future iterations do not depend on copying large previous conversations.

18. Challenge weak assumptions instead of blindly accepting them.

19. Remove redundant or cosmetic components when they do not provide measurable or logically defensible value.

20. The simplest system that produces comparable or superior robust performance should generally be preferred over unnecessary complexity.