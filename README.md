# Neuron Pruning with L-inf norm is better than with L-2 norm 💡✨
# -------------------------------------------
### As you know, Pruning is a process to compress the model without decrease the accuracy by neglect unimportant weights or neurons.
### To prune a neuron based on weight magnitude you can use the L-2 norm of the neuron’s weights.

### in this example, the author use neural network with just 4 hidden layers in Minst dataset and get accuracy around 90%. after pruning around 25% of neurons with L-2 norm, the accuracy became 88%. but with L-inf norm you can prune 40% to have 88% accuracy also. and if you prune 60% of neurons, the accuracy will drop 9% and became 80%.
![https://media.licdn.com/dms/image/D4D22AQH2TGY0CW7Xvw/feedshare-shrink_2048_1536/0/1696124009603?e=1701907200&v=beta&t=L54hZZtklXMBXg5s0uu6SKRRQkKnrce4gQ0YLNy18RA](https://github.com/Ahmed-G-ElTaher/Neuron-Pruning-with-L-inf-norm-is-better-than-with-L-2-norm-/blob/main/1696124009603.jpeg)


## So, why L-inf norm is better than L-2 norm ?
## why don't we use it ? also in Regularization for models ?


# it's related to the fact of. L-1 ≥ L-2 ≥ L-inf

## LinkedIn Post --->  https://www.linkedin.com/feed/update/urn:li:activity:7114118115470282752?utm_source=share&utm_medium=member_desktop
## Kaggle Code --->  https://www.kaggle.com/code/ahmedelkelany/pruning-a-neural-network)
