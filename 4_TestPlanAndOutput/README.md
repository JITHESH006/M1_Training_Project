## Test Plan

## High Level Test Plan

| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | status |
| --- | --- | --- | --- | --- | --- |
| 01 | Adding new patients details  | id,name | Record ipdated sucessfully | Record ipdated sucessfully | pass |
| 02 | Delete existed  patient  record | id=? | id found | id found | pass | 
| 03 | checking list records present in system| view records | list of records | list of records | pass |
| 04 | Search for particular patient record in system  | enter patient id | Record found | Record found | pass |
| 05 | checking rooms availability | Room no | Room available | Room availble | 
| 06 | Login into the system | Password | Accepted |Accepted| pass |
| 07 | Exit from the system | Exit | Exited | Exited | pass |


## Low Level Test Plan



| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | status |
| --- | --- | --- | --- | --- | --- |
| 01 | Delete patient record not existed  | id | id not found | id not found | pass |
| 02 | Login into the system | Password | Denied | Denied | pass | 
| 03 | checking rooms availability| Room no | Room not available | Room not available | pass |




