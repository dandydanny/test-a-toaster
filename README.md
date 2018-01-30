# test-a-toaster
A repository of ideas on how to test a common household electric bread toaster

## Basic but Important Functions

| Function | Test Case |
| ------------------- | --------- |
| Toasting bread | Does toaster able to warm up and brown (toast) bread slices? |
| Prevent burning of bread | Does toaster stop toasting automatically before bread is charred and ignited? |
| Ability to adjust degree of toast | Does toaster lightly brown the bread when set to low? Does it toast more when set to high? |
| (Top load slice toasters) Toast ejection | Does the toaster elevate the bread for easy retrival after toasting is complete |

## Safety Considerations

| Function | Test Case |
| ------------------- | --------- |
| No leakage of electrical current via cabinet | Measured voltage potential from toaster body to ground should be `0V`. No current flow allowed (`0μA`) |
| Over-temp shutoff | Does toaster shut off when temperature reaches an unsafe level? |
| Over-current shutoff | Should the toaster pull abnormally high current, does overcurrent protection disconnect toaster from power? |
