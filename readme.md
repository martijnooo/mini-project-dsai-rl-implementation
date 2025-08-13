![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# MINI-PROJECT | Build Your First RL Algorithm

## Mini Project Overview

This is a 2-day hands-on mini project where you will research, implement, and present a simple reinforcement learning algorithm. You'll work with classic RL problems and build your understanding from the ground up.

## Learning Objectives

By the end of this lab, you will be able to:
- Understand the fundamentals of reinforcement learning
- Implement a basic RL algorithm from scratch
- Apply your algorithm to a classic RL problem
- Analyze and present your results
- Identify appropriate tools and resources for RL development

## Day 1: Research and Implementation

### **Your Task**
Choose ONE of the following classic RL problems and implement a simple algorithm to solve it:

#### **Problem Options:**

1. **Multi-Armed Bandit**
   - Classic exploration vs exploitation problem
   - Recommended algorithms: ε-greedy, UCB, Thompson Sampling
   - Simple to implement and understand

2. **Grid World**
   - Agent navigates a grid to reach a goal while avoiding obstacles
   - Recommended algorithms: Q-Learning, SARSA, Value Iteration
   - Great for visualizing learning progress

3. **Frozen Lake**
   - Agent navigates a frozen lake to reach a goal without falling through holes
   - Available in OpenAI Gym
   - Good for discrete state spaces

4. **CartPole**
   - Balance a pole on a cart
   - Available in OpenAI Gym
   - Continuous observation space, discrete action space

5. **Taxi Problem**
   - Pick up and drop off passengers efficiently
   - Available in OpenAI Gym
   - Discrete states and actions

### **Requirements**
- Implement your chosen algorithm in Python
- Your solution should be able to learn and improve over time
- Include basic visualization of your results (learning curves, performance metrics)
- Document your code with comments explaining key concepts

### **Recommended Python Packages**
```bash
# RL-specific packages
pip install gym[classic_control]  # OpenAI Gym
pip install stable-baselines3     # Optional: for comparison
pip install pygame               # Optional: for custom visualizations

# Additional useful packages
pip install seaborn              # Better plotting
pip install jupyter              # For interactive development
pip install tqdm                 # Progress bars
```

### **Research Resources**
- **OpenAI Gym Documentation**: https://gym.openai.com/
- **Sutton & Barto Book**: "Reinforcement Learning: An Introduction" (free online)
- **GitHub Repositories**: Look for simple implementations to understand structure

#### **Day 1: Topic Research & Setup**
- Working Python implementation of your chosen algorithm
- Basic results showing your agent learning
- List of resources you used

## Day 2: Presentation and Discussion

- **Presentation Format**
Each student/team will present their work in **10 minutes** followed by **5 minutes** of Q&A.

### **Presentation Structure**

1. **Problem Introduction** (2 minutes)
   - What problem did you choose and why?
   - What makes this problem interesting for RL?

2. **Algorithm Explanation** (3 minutes)
   - Which algorithm did you implement?
   - How does it work conceptually?
   - What are the key parameters?

3. **Implementation Demo** (3 minutes)
   - Show your code running
   - Demonstrate learning progress
   - Display your visualizations

4. **Results and Analysis** (2 minutes)
   - How well did your algorithm perform?
   - What challenges did you encounter?
   - What would you do differently?

5. **Resources and Learning** (1 minute)
   - What resources were most helpful?
   - Key insights you gained

### **Evaluation Criteria**
- **Technical Implementation** (40%): Does the code work? Is it well-structured?
- **Understanding** (30%): Do you understand the algorithm and problem?
- **Presentation** (20%): Clear explanation and demonstration
- **Creativity/Insights** (10%): Novel approaches or interesting observations

## **Getting Started Tips**

### **Choosing Your Problem**
- **Beginners**: Start with Multi-Armed Bandit or simple Grid World
- **Intermediate**: Try Frozen Lake or Taxi Problem
- **Advanced**: Attempt CartPole or create your own environment

### **Implementation Approach**
- Start simple and build complexity gradually
- Test with small examples first
- Use print statements and visualizations to debug
- Don't worry about perfect optimization - focus on understanding

## Additional Resources

### **Online Platforms**
- **Google Colab**: Free GPU access for training
- **Kaggle Notebooks**: Pre-installed packages and datasets
- **GitHub**: Search for "[problem-name] reinforcement learning python"

## **Submission Requirements**

Pull request to the github repository the following :
1. Your Python code (well-commented)
2. A brief `Readme.md` report (1-2 pages) explaining your approach & resources used.

## **Bonus Challenges** (Optional)

- Compare multiple algorithms on the same problem
- Create your own custom environment
- Implement a more advanced algorithm (Deep Q-Learning, Policy Gradient)
- Add sophisticated visualizations or animations
- Analyze hyperparameter sensitivity

**Remember**: The goal is learning, not perfection. Focus on understanding the concepts and building something that works. Don't hesitate to ask for help when needed!

**Good luck, and enjoy your first dive into reinforcement learning!**