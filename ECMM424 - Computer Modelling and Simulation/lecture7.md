# Simulation Warm-Up Period and Output Analysis

## How to deal with Initial Transient Period

Four main methods for dealing with the initial transient:
- The initial conditions of the model are set such that the model starts from a steady-state.
- The model is run for a very long time, making the bias effect negligible.
- THe steady-state parameters are estimated from a short transient simulation run.
- THe model is run-in for a warm-up period until it reaches a steady-state and the data collected in the warm-up period are deleted.