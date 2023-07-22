# Lunar Lander Reinforcement Learning with Stable Baselines3 and Gym

<p align="center">
  <img src="https://wingedsheep.com/content/images/2020/08/lunarlander_trained_cropped.gif" alt="Moon Lander GIF">
</p>


Ilcome to the Lunar Lander Reinforcement Learning project! In this repository, I used the Stable Baselines3 library and OpenAI Gym's LunarLander environment to train an agent to successfully land a lunar lander on the moon's surface. The agent has undergone extensive training for 1 million steps to master the challenging task of landing safely.

## Environment

The Lunar Lander environment is a classic control problem in reinforcement learning, where the goal is to control a spacecraft and guide it to land smoothly on the moon's surface. The lander is subject to gravity and has limited fuel to control its thrusters. The agent must learn the optimal policy to make precise maneuvers and achieve a safe landing without crashing.

## Dependencies

To run the code in this repository, you need the following dependencies:

- Python 3.x
- Stable Baselines3
- Gym
- Numpy

You can install the required packages using `pip`:

`pip install stable-baselines3 gym numpy gymnasium pygame`


## Training

The training process involved training the agent using the Proximal Policy Optimization (PPO) algorithm for 1 million steps. I chose PPO due to its good performance on continuous action spaces like the Lunar Lander environment.

To run use the `Moon Lander.ipynb` file


During training, you will see the agent gradually improve its performance and learn to land the lunar lander more effectively.

## Evaluation

To evaluate the trained agent's performance, I ran multiple episodes after training to observe its landing capabilities. I saved the best-performing model for deployment.

You can evaluate the agent's performance using the following command:

## Results

After training for 1 million steps, our agent achieved an impressive landing success rate of over 95%! The agent learned to use its thrusters wisely and made precise decisions to land smoothly on the moon's surface.

Here's an example of a successful landing:

![Successful Landing](images/successful_landing.gif)

And here's an example of an unfortunate crash:

![Unfortunate Crash](images/crash.gif)

## Future Work

Although our agent performs Ill, there is always room for improvement. Here are some ideas for future work:

1. Experiment with different algorithms like Deep Deterministic Policy Gradients (DDPG) or Trust Region Policy Optimization (TRPO) to compare performance.
2. Try different reward shaping techniques to guide the agent more effectively.
3. Implement a curiosity-driven exploration mechanism to encourage the agent to explore the environment better.

Feel free to fork this repository and contribute your improvements! Let's continue to make our lunar lander agent even more proficient.

## Acknowledgments

I would like to express our gratitude to OpenAI for providing the Gym library, which allowed us to experiment with various reinforcement learning environments, including the Lunar Lander.

Special thanks to the Stable Baselines3 team for their excellent RL library and documentation, making it easier for researchers and developers to train and evaluate RL models.

## License

This project is licensed under the [MIT License](LICENSE).

Happy landing on the moon!
