# TorchQLearning
![TorchPlaysCatch](https://github.com/SeanNaren/TorchQLearningExample/raw/master/images/torchplayscatch.gif)

(Not the best player in the world!)

Torch plays catch! Based on Eder Santanas' [implementation](https://gist.github.com/EderSantana/c7222daa328f0e885093) in keras. Highly recommend reading his informative and easy to follow blog post [here](https://edersantana.github.io/articles/keras_rl/).

Agent has to catch the fruit before it falls to the ground. Agent wins if he succeeds to catch the fruit, loses if he fails.

## Dependencies

To install torch7 follow the guide <a href="http://torch.ch/docs/getting-started.html">here</a>.

Other dependencies can be installed via luarocks:

<a href="https://github.com/torch/optim">Optim: numeric optimization package for Torch</a>:
```
luarocks install optim
```

## How to run

To train a model, first un-comment out the Main() call at the end of TorchQLearningExample.lua. Then run the TorchQLearningExample.lua script.

## Visualization
Visualization implemented in [itorch](https://github.com/facebook/iTorch). Click [here](https://github.com/facebook/iTorch#requirements) for install instructions.

To run, type into terminal:

```
itorch notebook
```

Make sure in the TorchQLearningExample.lua script, you comment out Main(), otherwise it will train a new model.

And navigate to the TorchPlaysCatch.pynb. Run the kernel (you must've installed the above dependencies).

Eder Santana, Keras plays catch, (2016), GitHub repository, https://gist.github.com/EderSantana/c7222daa328f0e885093
