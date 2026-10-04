# EXPERIMENT NO: 1
# VERIFICATION OF KIRCHHOFF'S LAWS

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit using Proteus software.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit using Proteus software.

## APPARATUS REQUIRED

| S.No. | Components | Range / Value | Quantity |
|------:|------------|---------------|---------:|
| 1 | Resistor | 10 Ω, 20 Ω, 30 Ω, 50 Ω | 7 |
| 2 | Voltmeter (DC) | 0–30 V | 3 |
| 3 | Ammeter (DC) | 0–5 A | 5 |
| 4 | DC Voltage Source | 0–100 V | 2 |
| 5 | Connecting Wires | As required | As required |
| 6 | Proteus 8 Professional | Simulation Software | 1 |

## THEORY

### Kirchhoff's Voltage Law (KVL)

Kirchhoff's Voltage Law states that the algebraic sum of all voltage
rises and voltage drops around any closed loop in an electrical circuit
is zero.

Mathematically,

ΣV = 0

Therefore, the sum of the voltage supplied by the source and the voltage
drops across the resistors in a closed loop is zero.

### Kirchhoff's Current Law (KCL)

Kirchhoff's Current Law states that the algebraic sum of currents at any
junction in an electrical circuit is zero.

Mathematically,

ΣI = 0

Therefore, the total current entering a junction is equal to the total
current leaving the junction.

## PROCEDURE

### a. KVL

1. Construct the circuit as shown in the KVL circuit diagram using Proteus software.
2. Set the DC voltage source to the required input voltage.
3. Check the connections of the ammeter and voltmeters.
4. Run the simulation.
5. Record the current shown by the ammeter.
6. Record the voltage across each resistor using the respective voltmeters.
7. Verify KVL by comparing the source voltage with the sum of the voltage drops across the resistors.

### b. KCL

1. Construct the circuit as shown in the KCL circuit diagram using Proteus software.
2. Set the DC voltage source to the required input voltage.
3. Check the connections of all the ammeters at the respective branches.
4. Run the simulation.
5. Record the current entering the junction.
6. Record the currents in the individual branches.
7. Verify KCL by comparing the incoming current with the sum of the outgoing branch currents.

## CIRCUIT DIAGRAM

### KVL Circuit

<img width="1098" height="701" alt="KVL Circuit" src="https://github.com/user-attachments/assets/12b6beac-8901-4467-834a-6014c8c0082a" />

### KCL Circuit

<img width="1169" height="787" alt="KCL Circuit" src="https://github.com/user-attachments/assets/bd3d0626-12f0-426a-8233-85173d5430da" />

## OUTPUT

### KVL Simulation Output

<img width="1128" height="692" alt="KVL Simulation" src="https://github.com/user-attachments/assets/5ff1101c-8321-4c6e-8807-ce6f8b570009" />

### KCL Simulation Output

<img width="1168" height="768" alt="KCL Simulation" src="https://github.com/user-attachments/assets/84e76f15-f41b-4f3d-ac24-ad11e662fd8f" />

## TABULATION

### KVL

| S.No. | Input Voltage (V) | Current (A) | V₁ (V) | V₂ (V) | V₃ (V) | V₁ + V₂ + V₃ (V) |
|------:|------------------:|------------:|-------:|-------:|-------:|-------------------:|
| 1 | 50 | 0.50 | 25 | 15 | 10 | 50 |

### KCL

| S.No. | Input Voltage (V) | I₁ (A) | I₂ (A) | I₃ (A) | I₄ (A) | I₂ + I₃ + I₄ (A) |
|------:|------------------:|-------:|-------:|-------:|-------:|-------------------:|
| 1 | 100 | 2.94 | 0.59 | 1.18 | 1.18 | 2.95 |

## RESULT

Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.


