## Install

`pip install gym`

`pip install pygame`

## Test 

```
import gym

env = gym.make('CartPole-v1', render_mode="human")

env.reset()

for _ in range(100):
    env.render()
    env.step(1) # take a random action
```
