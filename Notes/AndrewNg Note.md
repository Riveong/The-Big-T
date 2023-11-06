## Trivia
- not very widely applied
- lots of research backing it up

## Example
- Autonomous Helicopter

position of helicopter -> how to move control sticks
state s -> action a

in supervised learning:
x (bunch of observation state) -> y (best action)
this is very ambiguous what is the exact one right action to take with supervised learning. Tilt to left or right, Very diffcult to get dataset

in RL:
x = reward function:

reward function is going to tell the agent when is it doing good and when is it doing poorly

<b>Analogy</b>: Training puppy / dog, Give them rewards when puppy do something good. Give them treats! or call them good dog when they do something good and call them bad dog when they do something bad like pooping on top of your mom's head for example.

<b>Variety of use RL</b>
- Controlling robots
- Factory optimization
- Financial (stock) trading
- Playing games

## Simplified and Deep Example
Mars rover example
We will develop reinforcement learning, In this app the rover can be in any of 6 position
the position of the rover = state

## Why Reinforcement Learning is Important
Because you have only to say what to do to the agent rather than how to do it. and specifying reward function rather than optimal action. So it will give you more flexibility to work with.

## Reward Function
- When the helicopter doing well we can give it +1 point
- When the helicopter doing poor -1 or when crash -1000