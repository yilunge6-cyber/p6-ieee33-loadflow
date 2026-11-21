# P6 working notes

## Day 1: concepts
- Per-unit:
- Bus types (slack vs PQ):
- Load flow:
- Voltage drop:
- Losses:
- Faults and sequence impedances:

## Day 2: base case
- pandapower version: 3.5.6
- Buses / lines in service / ties:
- Total load (MW, Mvar):
- Total losses (kW):
- Minimum voltage (pu) and IEEE bus:
- Buses below 0.95 pu:
- Substation supply - load = losses? (check):
- Why the voltage plot jumps at buses 19, 23, 26:

## Day 3: scenarios
- Predictions before running:
- Peak/nominal loss ratio (vs 1.69):
- Light/nominal loss ratio (vs 0.25):
- Why they differ:

## Day 4: faults
- Assumptions and why:
- Bus 1 hand calc vs tool:
- Bus 18 hand calc vs tool:
- What a protection engineer takes from this:

## Day 5: sensitivity and fix
- What each assumption changes:
- Chosen capacitor bus and why:
  I chose bus 30 because it minimises losses, which save money every hour, while still raising minimum voltage from X to Y pu.
- Before/after result sentence:
- What the fix did not solve:

## Problems I ran into
- Day 1: pip warning about pandas version (harmless)

## Questions to look up
-
