This report discusses a technical study of an autonomous
drone delivery system trained using Approximate Q-learning
with linear function approximation. We model this task as
a finite Markov Decision Process (MDP) within a Gymcompatible
simulation. The agent learns a navigation policy
that balances path efficiency, obstacle avoidance, and successful
task completion based on a defined reward function.
Linear approximation helps us deal with the scalability challenges
of tabular Q-learning in navigation problems that involve
large state spaces. Experimental results show that the
system converges to a stable and interpretable policy that can
complete the delivery task, but they also highlight known stability
issues with off-policy learning and function approximation.
