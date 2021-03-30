Part 1:  5/5

Part 2:  4/5

In 25.4, you missed the extra condition that "if the length of stay is zero, then it should not count".  You've got that covered with your "diagnosis == Observation" test, but not in the scenario where the patient's admit and discharge are the same day.  In that case, it should also not be counted in the total number of items.

