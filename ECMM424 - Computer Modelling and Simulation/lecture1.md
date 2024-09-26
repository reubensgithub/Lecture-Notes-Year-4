# Computer Simulation

### Focusing on Discrete-Event Systems and Model Design

1. **Generation of input data** using random number generation.
2. **Development of system simulation** based on the knowledge of the system and inputs, while considering the order of occurrence of events in the system.
3. **Output statistical analysis and model validation**.

---

## Simulation Overview
- **Simulation**: Imitation of the operations of a real-world process or system over time.
- **Artificial history**: Generation of an artificial history of a system.
- **Observation**: Observing the artificial history to understand the operating characteristics of the real system.

Modern simulation is a computer program that mimics the behavior of a real-world **system** over time, including its inputs and outputs.

---

### Applications of Simulation

- **Manufacturing applications**
- **Construction engineering**
- **Military applications**
- **Transportation and distribution applications**
- **Climate and weather forecast**
- **Design of communication networks**

---

## Systems

### System:
- A group of objects or components that interact towards the accomplishment of some logical goals.

### Entity:
- Any object or component in the system that requires explicit representation, e.g., a server, a customer, a machine.
  - **Attributes** are the properties of the entity.
  - **Attributes** are represented by state variables.

### Activity:
- Set of actions, e.g., check balance at a bank, serve a customer.

### State of a System:
- Collection of variables and their values necessary to describe the system at a particular time.

---

## Discrete vs Continuous

- **Discrete**: State variables change instantaneously at separated points in time.  
  *Example*: A bank model changes when a customer arrives or departs.

- **Continuous**: State variables change continuously as a function of time.  
  *Example*: An airplane model where position and velocity change continuously.

---

## Models

### Mathematical Model:
- Uses symbolic notation and mathematical equations to represent a system.

### Physical Model:
- Models whose physical characteristics resemble those of the actual system. It looks or feels like the real thing.

### Analytical Solution:
- If the model is simple enough, mathematical approaches (e.g., calculus, algebra, probability theory) can be used.

### When to Use Simulation:
- **Complex dynamic systems**: Analytical models require too many simplifications and may not be valid.
- **Incomplete formulation**: No analytical solution exists.
- **Complex procedures**: Mathematical procedures (e.g., partial differential equations) are too complex; simulation provides a simpler solution.

### Problems with Simulation:
- Simulations can be **complex and error-prone**.
- Simulations can take a **long time** to execute.
- Simulation produces **approximate answers**.
- **Analytical models** are less flexible but exact and efficient.

---

## Simulation Models: Stochastic vs Deterministic

### Deterministic:
- No probabilistic components or random variables.
- Fixed inputs are known.
- *Example*: Patients arrive at a dentist’s office at their scheduled time.

### Stochastic:
- Involves random variables as inputs.
- Random inputs lead to random outputs.
- *Example*: Queueing systems.

---

## Simulation Models: Static vs Dynamic

### Static Simulation:
- Time plays no role.
- *Example*: Monte Carlo method for calculating the value of Pi.

### Dynamic Simulation:
- Represents a system as it evolves over time.
- *Example*: Simulation of a bank from 9am to 4pm.

---

## Steps in a Simulation Study

1. **Problem Formulation**:
   - Understand the problem to be addressed by simulation.
   - Reach agreement on the problem formulation between the policy maker and the analyst.

2. **Setting Objectives and Project Plan**:
   - Define the objectives and questions to be answered by the simulation.
   - Determine whether simulation is appropriate.
   - Formulate the project plan.

3. **Model Conceptualization**:
   - The model is an abstract representation of the system.
   - Determine what to include and exclude from the model.
   - Decide on abstractions and the level of detail required.

4. **Data Collection**:
   - The more data you collect, the more precise your model will be.

5. **Model Translation**:
   - Program the model into a computer language, or use special-purpose simulation software.

6. **Verification**:
   - Ensure the computer program is correctly prepared for simulation.
   - Verify the accuracy of input parameters and logical structure.
   - Check if the computer program performs correctly.

7. **Validation**:
   - Determine if the model is an accurate representation of the real system.
   - Validation is an iterative process of comparing the model to the actual system.

8. **Experimental Design**:
   - Decide on the length of the initialization period.
   - Determine the length of simulation runs.
   - Determine the number of replications to be made for each run.

---
