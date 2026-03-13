# Conveyor Control Simulation using Siemens S7-1200

Siemens S7-1200 conveyor control simulation developed in TIA Portal V20 using S7-PLCSIM V20.

## Software Used

* TIA Portal V20
* S7-PLCSIM V20 Standard

## PLC Used

* SIMATIC S7-1200
* CPU 1214C DC/DC/DC

## Project Functions

* Motor start/stop latch
* Product counting using CTU counter
* Conveyor stop at batch count = 5
* Reject output activation
* Batch complete alarm
* Timer-based jam alarm
* Reset acknowledgment

## Simulation Workflow

Start → Conveyor Runs → Product Count → Count = 5 → Conveyor Stops → Alarm ON → Reset

## Validation Completed

* Idle state verified
* Counter reached preset value
* Conveyor stopped automatically
* Outputs activated correctly
* Reset restored system state

## Project Screenshots
![Counter CV5](02%20counter%20cv5.png)


![Outputs Active](03%20outputs%20active.png)

## Documentation
[Full Project PDF](Conveyor%20Control%20Project.pdf)


## Author
Mohammad Shahul
LinkedIn: [linkedin.com/in/mohammadshahul](https://linkedin.com/in/mohammadshahul)
