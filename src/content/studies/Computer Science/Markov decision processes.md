An MDP is made up of states, $s\in{S}$, and actions, $a\in{A}$, with transition functions, $T(s,a,s')$ defining the probability of an action leading successfully to a new state $s'$, and a reward function, $R(s,a,s')$ that gets regarded

## Value iteration

## Policy iteration

$$V^{*}(s)=\max\limits_{\alpha}\sum\limits_{s'}{T(s,a,s')[R(s,a,s')+\gamma{V^{*}(s')}]}$$

The method utilised to solve MDPs in the world nowadays is actually [[Computer Science/Reinforcement learning|Reinforcement learning]], where we can solve for environments for which we don't know the transition and/or reward functions, or it is simply not efficient to store values for an entire state space, or the states and actions are continuous in nature.