## Test Plan

## High Level Test Plan

| Test ID | Description | INPUT |	 Output | status |
| --- | --- | --- | --- | --- |
| 01 | Adding new patients details  | id,name  | Record ipdated sucessfully | pass |
| 02 | Delete existed  patient  record | id=? | id found | pass | 
| 03 | checking list records present in system | list of records | list of records | pass |
| 04 | Search for particular patient record in system  | enter patient id  | Record found | pass |
| 05 | checking rooms availability | Room no | Room available | Room availble | 
| 06 | Login into the system | Password | Accepted| pass |
| 07 | Exit from the system | Exit |  Exited | pass |


## Low Level Test Plan



| Test ID | Description |  INPUT| Output | status |
| --- | --- | --- | --- |  --- |
| 01 | Delete patient record not existed  | id | id not found  | pass |
| 02 | Login into the system | Password | Denied  | pass | 
| 03 | checking rooms availability| Room no | Room not available  | pass |




