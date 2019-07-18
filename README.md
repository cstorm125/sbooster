# Traffic Light Control Simulation

We are simulating traffic flow of a simplified Silom-Sathorn intersection network for 1 hour. The performance metric is average velocity of all cars in the scenario averaged across all timesteps (1 second per timestep). We demonstrated that by using an **actuated control logic** (switches the lights when a significant gap is presented among vehicles) as opposed to static control logic (switches the lights every fixed interval regardless of traffic conditions). We can see that using actuated control can **increase average velocity of all vehicles across all timesteps by 34%.**

## Requirements

* [flow](https://github.com/flow-project/flow)