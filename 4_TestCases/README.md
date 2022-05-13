# Test Cases : 

## High Level Test Cases :

|**Test ID**|**Description**|**Exp. input**|**Exp. output**|**Actual output**|**Pass/Fail**|
| :- | :-: | :-: | :-: | :-: | :-: |
|HLT_01|At The Time of ON Engine(ACC mode)|Pressed BUTTON ONCE|ON Engine|ON Engine|PASS|
|HLT_02|At The Time of OFF Engine(off mode)|Pressed BUTTON TWICE|OFF Engine|OFF Engine|PASS|
|HLT_03|At The Time of ON Wiper|Pressed BUTTON THREE Times|ON Wiper|ON Wiper In ClockWise Direction|PASS|
|HLT_04|At The Time of OFF Wiper|Pressed BUTTON FOUR Times|OFF Wiper|OFF Wiper In Anti ClockWise Direction|PASS|

## Low Level Test Cases :

|**Test ID**|**Description**|**Exp input**|**Exp output**|**Actual output**|**Pass/Fail**|
| :- | :-: | :-: | :-: | :-: | :-: |
|LLT_01|ON Engine Check Condition|Pressed BUTTON ONCE|ON All LED|ON All LED As Per ENCRYPTION|PASS|
|LLT_02|OFF Engine Check Condition|Pressed BUTTON TWICE|OFF All LED|OFF All LED As Per ENCRYPTION|PASS|
|LLT_03|ON Wiper Check Condition|Pressed BUTTON THREE Times|ON LED Once ClockWise|ON LED Once In ClockWise Direction As Per ENCRYPTION|PASS|
|LLT_04|OFF Wiper Check Condition|Pressed BUTTON FOUR Times|ON LED Once Anti ClockWise|ON LED Once In Anti ClockWise Direction As Per ENCRYPTION|PASS|

