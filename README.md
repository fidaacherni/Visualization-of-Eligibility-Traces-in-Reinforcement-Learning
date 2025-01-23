🎯 Overview
This project focuses on visualizing eligibility traces, a key concept in reinforcement learning (RL), to bridge the gap between Monte Carlo (MC) methods and Temporal Difference (TD(0)) learning through the generalization TD(λ). The primary goal is to develop a user-friendly, interactive visualization that helps students and practitioners intuitively understand how eligibility traces impact learning and decision-making in RL.

🛠 Objective
1- Explain and visualize eligibility traces by highlighting the role of λ (trace decay factor) and 𝛾 (discount factor).
2- Showcase the transition from MC and TD(0) to TD(λ), explaining their limitations and how TD(λ) addresses them.
3- Provide a gridworld simulation where an agent's trajectory and eligibility traces are dynamically displayed.
4- Analyze agent performance across different hyperparameter combinations:
   - High λ and high 𝛾.
   - Low λ and low 𝛾.
   - High λ and low 𝛾.
   - Low λ and high 𝛾.

🔍 Key Features
1- Dynamic Heat Map Visualization:
   - The grid highlights the agent's path in blue, with recently visited states brightly colored, and dimming as the trace decays.
   - A time slider allows users to view the agent's steps throughout an episode.

2- Hyperparameter Testing:
Analyze how λ and 𝛾 impact:
  - Accumulated reward over episodes.
  - Convergence speed.
  - Agent behavior.
    
3- Performance Comparison:
  - Generate plots of accumulated reward (y-axis) vs. number of episodes (x-axis).
  - Compare performance across:
    - MC.
    - TD(0).
    - TD(λ) with varying λ and 𝛾.
      
4- Real-World Applications:
  - Highlight use cases where eligibility traces can improve learning (e.g., robotics, navigation, and adaptive systems).

5- Gamification:
  - Emphasize the winning agent with optimal hyperparameters.
  - Count steps per episode to identify the first agent reaching the goal in the fewest steps.

6- Alternative Eligibility Trace Computations:
  - Demonstrate various ways to compute z-values and their effects on learning.

📈 Insights
1- λ and 𝛾 Analysis:
   - High λ and high 𝛾:
     - Strong long-term credit assignment.
     - May lead to slower convergence.
   - Low λ and low 𝛾:
     - Short-term focus but faster learning.
     - Mixed settings reveal the balance between exploration and exploitation.
     
2- MC vs. TD(λ):
   - MC methods require full episodes, while TD(λ) enables learning mid-episode.
   - TD(0) converges faster but lacks long-term credit assignment.

3- Visualization Outcomes:
   - Clear visualization of how recent steps contribute more to reward attribution.
   - The heat map provides an intuitive understanding of trace decay.

This project offers an interactive and educational visualization tool for understanding eligibility traces, their role in RL, and their practical implications. By combining clear visualizations with performance analysis, it provides a comprehensive resource for students and researchers to explore the benefits and limitations of TD(λ).
