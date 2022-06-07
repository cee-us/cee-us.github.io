## Curious Exploration via Structured World Models Yields Zero-Shot Object Manipulation

**Abstract**: It has been a long-standing dream to design artificial agents that explore their environment efficiently via intrinsic motivation, similar to how children perform curious free play. Despite recent advances in intrinsically motivated reinforcement learning (RL), sample-efficient exploration in object manipulation scenarios remains a significant challenge as most of the relevant information lies in the sparse agent-object and object-object interactions. In this paper, we propose to use structured world models to incorporate relational inductive biases in the control loop to achieve sample-efficient and interaction-rich exploration in compositional multi-object environments. By planning for future novelty inside structured world models, our method generates free-play behavior that starts to interact with objects early on and develops more complex behavior over time. Instead of using models only to compute intrinsic rewards, as commonly done, our method showcases that the self-reinforcing cycle between good models and good exploration also opens up another avenue: zero-shot generalization to downstream tasks via model-based planning. After the entirely intrinsic task-agnostic exploration phase, our method solves challenging downstream tasks such as stacking, flipping, pick & place, and throwing that generalizes to unseen numbers and arrangements of objects without any additional training.

### Intrinsic Phase of CEE-US: Free Play
#### In the Construction environment:

### Extrinsic Phase of CEE-US: Solving Downstream Tasks Zero-Shot
We showcase the zero-shot generalization of our method to challenging object manipulation tasks. Thanks to the combinatorial generalization capabilities of Graph Neural Networks, we can apply the learned world model to solve tasks with more or less than 4 objects, which is the number of blocks seen during free play time. 

#### Stacking:

#### Throwing:

#### Flipping:

#### Pick and Place:
