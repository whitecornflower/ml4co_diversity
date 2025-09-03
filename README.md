# ml4co_diversity
This piece of code focuses on improving the **diversity of Diffusion models for the Traveling Salesman Problem (TSP)**.  
The goal is to design a single model that can handle **TSP instances of varying distributions and scales**, improving generalization and robustness.

### Codebase

The project is based on the [Fast-T2T](https://github.com/Thinklab-SJTU/Fast-T2T) framework.

### Modification
Added a standard Feed-Forward Network (FFN) layer to the original GNN model.  

### Future Step
Add a Mixture of Experts (MoE) module by replacing the single FFN with multiple FFNs and a gating network.
