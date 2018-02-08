# test-a-toaster
A repository of ideas on how to test a common household electric bread toaster

## Main Functions

| Function | Test Case | Acceptable Value |
| ---------| --------- | ---------------- |
| Toasting bread | Does toaster able to warm up and brown (toast) bread slices? | True |
| Prevent burning of bread | Does toaster stop toasting automatically before bread is charred and ignited? | True |
| Ability to adjust degree of toast | Does toaster lightly brown the bread when set to low? Does it toast more when set to high? | True |
| (Top load slice toasters) Toast ejection | Does the toaster elevate the bread for easy retrival after toasting is complete | True |

## Safety Considerations

| Function | Test Case | Acceptable Value |
| -------- | --------- | ---------------- |
| No leakage of electrical current via cabinet and controls | Measured voltage potential from toaster body to ground should be `0V`. No current flow allowed (`0μA`): can voltage and/or current be detected? | False |
| Over-temp shutoff | Artificially create over-temp condition using combustable or very hot material. Does toaster shut off when temperature reaches an unsafe level? | True |
| Over-current shutoff | Artificially create over-current condition by short circuiting current flow after protection circuitry: does overcurrent protection disconnect toaster from power? | True |
| Exterior casing should not reach scalding temperatures | During normal toasting operation, external casing temperature should not exceed 44 °C (111 °F) | True |

## Usability

| Function | Test Case | Acceptable Value |
| -------- | --------- | ---------------- |
| Accomodates common bread slice thickness | Bread slot should accept thick and thin bread slices | True |
| Able to hold thin slices of bread at center | Mechanism to center thin slices of bread at equidistant between heater element on both sides | True |

## Durability and Reliability

| Function | Test Case | Acceptable Value |
| -------- | --------- | ---------------- |
| Case should withstand typical cleaning methods without damage | Wash exterior casing with dish detergent and Scotch Brite pads. Any visible damage? | False |
| Case should keep its original appearance as unit ages | Perform accelerate age test (usage repetition, high temp conditions). Does the case discolor or warp? | False |
