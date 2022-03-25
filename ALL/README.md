# Car Direction Indicators

# Description

Its an automatic and manual car direction indicating system.Based on the steering angle, respective indicator light automatically gets ON/OFF. This automatic signal will be useful when the driver/rider fails to put the indicator while entering the road from parking, during U turn, reversing the vehicle, both the indicator light will be ON (if the driver/rider puts wrong direction indication while turning), when the driver/rider is unable to put the indication during sudden turn.

# Requirements

## High Level Requirements
| **ID** | **Description** |
| --- | --- |
| HLR1 | It shell ON/OFF the indicators by manually operating the switch. |
| HLR2 | It shell ON/OFF the indicators automatically based on the angle of the steering. |

## Low level Requirements

| **HLRID** | **LLRID** | **Description** |
| --- | --- | --- |
| HLR1.1 | LLR1 | It shell switch on the left indicators if the switch is pressed left side.  |
| HLR1.2 | LLR2 | It shell switch on the right indicators if the switch is pressed right side.  |
| HLR1.3 | LLR3 | It shell switch off the indicators if the switch is off.  |
| HLR2.1 | LLR1 | It shell on the left indicators when the angle of the steering is >=135 degrees. |
| HLR2.1 | LLR1 | It shell on the right indicators when the angle of the steering is <=45 degrees. |
| HLR2.2 | LLR2 | It shell off the  indicators when the angle of the steering is >=45 and <=135 degrees. |

# SWOT Analysis


# 5W's and 1H

## what:
## why:
## when:
## where:
## who:
## How:
