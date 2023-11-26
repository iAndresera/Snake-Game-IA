# Snake-Game-IA
This project involves creating a game for artificial intelligence.
where it learns gradually to play and perfect its technique. 
Additionally, you can track the AI's progress throughout the process.

Environment Validation:
Validation tests to ensure that the environment accurately reflects the game rules.
Adjustments as needed.
Phase 2: Implementation of the Learning Algorithm
Algorithm Selection:
Research and selection of the most suitable reinforcement learning algorithm for the project.
Neural Network Configuration:
Design and implementation of the neural network architecture for the AI.
Configuration of hyperparameters.
Initial Training:
Commencement of AI training in the simulation environment.
Monitoring and adjustment of parameters based on initial performance.
Algorithm Optimization:
Fine-tuning of reward and penalty functions.
Optimization of the neural network structure to enhance learning efficiency.
Phase 3: Optimization and Evaluation
Evaluation of AI performance in terms of score and moves.
Adjustment of network and parameters to improve decision-making.
Generalization Tests:
Assessment of AI performance in different environment configurations.
Ensuring the ability to generalize learned skills.
Final Report Preparation:
Detailed documentation of methodology, results, and conclusions.
Inclusion of source code and configuration.
TESTS
1. Functionality Tests:
Basic Movements: Verify that the AI can perform basic movements (up, down, left, right) efficiently.
Food Collection: Ensure that the AI can identify and strategically collect food.
Collision Avoidance: Evaluate the AI's ability to avoid collisions with itself and obstacles in the environment.
2. Performance Tests:
Maximum Score: Confirm that the AI can achieve a maximum score in the game.
Space Utilization Efficiency: Evaluate how efficiently the AI uses the board space to maximize length and score.
3. Generalization Tests:
Varied Scenarios: Test the AI in different environment configurations to assess its adaptability and generalization capability.
Speed Changes: Modify the game speed to ensure the AI can adjust its strategy accordingly.
4. Real Environment Tests:
Consistency with Simulation Environment: Verify that the AI's behavior in the real environment is consistent with training in the simulation environment.
Adaptability to Changing Conditions: Evaluate the AI's ability to adapt to environmental conditions not present during training.
5. Stability Tests:
Execution Time: Check the stability and performance of the AI during prolonged executions.
Error Handling: Evaluate the AI's ability to handle unexpected situations or errors in the environment.
6. Specific Strategies Tests:
Strategy Analysis: Analyze specific strategies used by the AI in certain scenarios and verify their effectiveness.
Parameter Sensitivity: Evaluate how parameter variation affects the AI's performance.
7. Hardware Performance Tests:
Execution Speed Optimization: Assess the AI's performance in different hardware configurations to ensure efficiency.
IMPLEMENTATION

1. Development Environment Setup:
   - Install Python and necessary libraries.

2. Design and Implementation of Simulation Environment:
   - Create classes to represent the snake, food, and obstacles.
   - Implement the reward and penalty system.
   - Develop a graphical interface or visualization to observe the game and AI performance.

3. Implementation of the Learning Algorithm:
   - Select a reinforcement learning algorithm, such as DQN, and configure the neural network.
   - Define the reward function and necessary data structures.

4. Initial Training of the AI:
   - Start the simulation environment and train the AI.

5. Continuous Optimization and Evaluation:
   - Refine the reward function and adjust the neural network architecture.
   - Evaluate AI performance in different scenarios and ensure learning convergence.

6. Generalization Tests:
   - Develop diverse test scenarios to evaluate the AI's ability to adapt to different game conditions.
   - Adjust the AI based on the results of generalization tests.

7. Integration into the Real Environment:
   - Implement the trained AI in a real game environment.
   - Validate the consistency of behavior between the simulation and the real environment.

8. Real-Time Monitoring:
   - Implement a monitoring system to observe the AI's behavior during real-time execution.
   - Correct any potential discrepancies between simulation and real environments.

9. Documentation and Presentation:
   - Document the code, architecture, and results in detail.
   - Prepare a presentation to share achievements, challenges, and lessons learned with the team and stakeholders.

This implementation is a general outline and may require specific adjustments based on the exact project details.

DELIVERY AND EVALUATION

1. PROJECT DELIVERY:
   Documentation:
   - Final Report: Detailed documentation of methodology, algorithms used, and neural network architecture.
   - Implementation description, highlighting challenges encountered and applied solutions.
   - Inclusion of graphs, tables, and visualizations illustrating performance and AI evolution.
   - User guide detailing the execution and reproduction process of the project.
   - Highlight achievements, challenges overcome, and lessons learned.

2. PROJECT EVALUATION:
   AI Performance:
   - Score and Efficiency: Evaluate the AI's ability to achieve high scores and make efficient moves in the game.
   - Generalization: Analyze how the AI performs in different scenarios and its ability to generalize learned skills.
   - Adaptability to the Real Environment:
     - Consistency with Simulation: Verify that the AI's behavior in the real environment is consistent with training in the simulation environment.
     - Adaptability to Changing Conditions: Evaluate the AI's ability to adapt to environmental conditions not present during training.

   Stability and Efficiency:
   - Runtime: Analyze the stability and performance of the AI during prolonged executions.
   - Error Handling: Evaluate how the AI handles unexpected situations or errors in the environment.

   Specific Strategies:
   - Strategy Analysis: Analyze specific strategies used by the AI in certain scenarios and verify their effectiveness.
   - Parameter Sensitivity: Evaluate how parameter variation affects the AI's performance.

3. COMMENTS AND IMPROVEMENTS:
   - Receive feedback from the team and stakeholders.
   - Identify areas for improvement and potential project expansions.
   - Plan future improvements and possible practical applications of acquired knowledge.

Overall evaluation will be based on the AI's ability to learn and perform efficiently in the Snake game, as well as its adaptability to different situations and environments. Effective documentation and presentation are crucial for clearly and persuasively communicating project achievements and lessons learned.

Maintaining a project to teach artificial intelligence to play Snake involves managing ongoing updates, corrections, and improvements to ensure the AI continues to perform efficiently and can adapt to changes in requirements or the environment. Here are some considerations for project maintenance.


**MAINTENANCE**

1. **Updates:**
   - **Regular Code Review:** Periodic code reviews to identify potential issues, enhance readability, and apply updated software development practices.
   - **Library Updates:** Keep libraries and dependencies up to date to leverage new features and bug fixes.

2. **Error Management:**
   - **Continuous Monitoring:** Establish continuous monitoring systems to quickly identify and address potential issues or errors.
   - **Error Handling Improvement:** Enhance the AI's ability to handle unexpected situations or errors in the environment.

**PROJECT SCOPE**

The scope of the project to teach an artificial intelligence (AI) to play Snake includes various aspects related to the design, implementation, training, and evaluation of the AI in the specific context of the Snake game. The project scope includes:
- Design of the simulation environment.
- Implementation of the learning algorithm.
- AI training.
- Continuous optimization and evaluation.
- Ongoing deployment and documentation.
- Continuous maintenance and improvements.
- Testing and evaluations, all mentioned and explained previously.

**TIME:** 1 month
**COSTS:** 0

**Instructions and Recommendations:**
- Download and unzip the .rar file Project Snake AI.
- Unzip a folder with 5 files.
- The file named Snake Game (For humans) is for testing the game manually.
- To start the AI training, open the folder from the cmd, right-click, and open in the terminal, or open the cmd and type the project folder path.
- Once inside the folder from the cmd, run the file IA.py.
- After that, the AI will start training, showing on-screen how the AI moves during training, a progress chart, and in the cmd, you'll see the generation, maximum score, and the score achieved in that attempt.
- It's not recommended to move the windows showing the AI's progress too much, as it could cause an abrupt program closure.
- Review the code and ensure that the pygame, matplotlib, IPython, numpy, random, and torch libraries are installed to avoid issues when testing the AI.
