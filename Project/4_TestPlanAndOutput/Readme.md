# TEST PLAN

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  HLT_01       |Ultrasonic sensor |  In range| object detected | success |Scenario Based |
|  HLT_02       | Power supply |	Power ON |	Display ON	|success	| Requirement based | 
|  HLT_03       | LCD display| Inputed Value by sensor | Shows Output in Display |success|Requirement based    |

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  LLT_01      |Range | 1000cm | Object not detected | Failed |Scenario based |
|  LLT_02       |Range  | 300mm | Object detected | Success |Scenario based    |
|  LLT_03       |Range  | 854cm|Object not detected | Failed |Scenario based    |
| LLT_04 | Range | 70cm | Object detected | Success |Scenario based  |