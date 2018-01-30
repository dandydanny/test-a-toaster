# test-a-toaster
A repository of ideas on how to test a common household electric bread toaster

## Basic but Important Functions

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
