## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** |ANUKSHA S| **Reg. No.:** |26016254|
|---|---|---|---|
| **Date:** |18.11.26| **Batch / Section:** |260DJ121
|

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1536" height="860" alt="image" src="https://github.com/user-attachments/assets/d0d0c647-8a3f-42c9-9624-164627153d43" />

**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*

<img width="1031" height="835" alt="image" src="https://github.com/user-attachments/assets/c8e1a932-5dda-4aac-94b1-fab4e029b93a" />


## B. CROSS CONNECTION

### Circuit diagram

<img width="1536" height="874" alt="image" src="https://github.com/user-attachments/assets/f323a6e7-bbe8-4a1b-9c29-0faa5cbc3f29" />

**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*

<img width="1040" height="738" alt="image" src="https://github.com/user-attachments/assets/c66c7b0b-72c5-4bdc-8c1d-96589aa96b7f" />


## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/0e230011-8fb8-4a87-a768-632beeca1844" />


**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation

<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/8a9e0e1f-7830-4a58-bd00-ce40c619b851" />


**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
