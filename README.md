# RL-intro
In our k -armed bandit problem, each of the k actions has an expected or mean reward
given that that action is selected; let us call this the value of that action. We denote the
action selected on time step t as A t , and the corresponding reward as R t . The value then
of an arbitrary action a, denoted q ⇤ (a), is the expected reward given that a is selected:
q ⇤ (a) = E[R t | A t = a] .
If you knew the value of each action, then it would be trivial to solve the k -armed bandit
problem: you would always select the action with highest value. We assume that you do
not know the action values with certainty, although you may have estimates. We denote
the estimated value of action a at time step t as Q t ( a ). We would like Q t ( a ) to be close
to q ⇤ (a).
