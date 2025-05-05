# README #


# Using Behavior Trees in Risk Assessment Data

### What is this repository for? ###

This online Appendix is for the paper: Using Behavior Trees in Risk Assessment.

## Folder Structure: ##


```bash
main
│
├───BTCPP-pick&place (contains the Volvo Group Pick&Place mission created in Groot with the outputs from the FMEA annotated.)
│	├──pick_place_robot.xml (The file uses the XML-like language of BehaviorTree.CPP to express the pick&place mission.)
├───FMEA-results (contains the applied risk assessment results)
│ ├──Risk_Assment_BT.xlsx (The file contains the outputs of process-FMEA for the pick&place mission.)
└───img (figures for the pick&place mission extracted from Groot)
```
## The Pick&Place mission:
The figure shows the pick&place mission in Groot.
![Alt text](img/BT_mission_all.jpg)

The figure shows the pick&place mission in Groot after integrating the outputs from FMEA. The code for the below figure is [here](/BTCPP-pick%26place/pick_place_robot.xml).
![Alt text](img/BT_mission_annotated_Groot.jpg)

### Who do I talk to? ###
Razan Ghzouli(razan.ghzouli@chalmers.se)
