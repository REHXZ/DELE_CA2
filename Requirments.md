Here's the content formatted in Markdown:

---

### Submission Requirements

a) Jupyter notebook including your code, comments, and visualizations (.ipynb).

b) In addition, please save a copy of the Jupyter notebook as an .html file.

c) Include your best neural network weights (.h5 file).

d) A deck of presentation slides (.pptx file) for your project.

e) A statement indicating the contributions by each member of the group, including the percentage of workload for specific contributions.

---

**NOTE:** Each student must be well-versed with both Parts A and B. While you can consider splitting the workload, you will still be evaluated on everything in this CA. You cannot expect to only do one part but know little or nothing about the other part.

For Part C, you should submit your file as a Word (.docx) or PDF document. If you write your own codes, you must include them.


### PART A  Task
#### GAN Architectures for Image Generation

1. **Task Overview:**
   - Apply suitable GAN architectures to the problem of image generation.
   - Use the given dataset to create 260 small black-and-white images.
   - There should be 26 classes of images for you to generate.
   - You must submit your generated images.

2. **Evaluation of Generated Images:**
   - Implement methods to evaluate the quality of your images:
     - A simple “by-eye” or “eye-power” method: generate 50 images (or 49 images in a 7x7 grid) and manually count how many are acceptable. Categories could be "clear", "marginal", or "nonsense".
     - Consider other metrics/indicators for evaluation.
   
3. **Class-Specific Image Generation:**
   - Propose a method for generating images of a specific class if required.
   
4. **Color vs. Black-and-White Images:**
   - Discuss whether it would be easier or harder to produce better quality colored images compared to black-and-white ones.
   
5. **Difficulty of Classes:**
   - Identify which class(es) are relatively easier or harder to generate and explain why.

6. **Important Notes:**
   - Do not focus excessively on generating “perfect-looking images.” While image quality indicates the quality of your model, the process, workflow, planning, EDA, and evaluation analysis are more important.
   - As this is a pair-work project, discuss and optimize the GAN training process between yourselves, utilizing available computing resources for both of you.

---

### PART B: REINFORCEMENT LEARNING (45 marks)

#### Task
- Apply a suitable modification of deep Q-network (DQN) architecture to the problem.
- Your model should exert appropriate torque on the pendulum to balance it.
- You must use DQN and satisfactorily demonstrate its viability.
- You may consider other reinforcement learning architectures, if you wish, but only after successfully implementing DQN. Otherwise, any other non-DQN architecture will be rejected.
- Clearly plan your approaches and systematically optimize your solutions.

#### Considerations:
- What hyperparameters can you tune?
- Is one trial enough or should you repeat the trials? Why?
- How do you conclusively demonstrate your so-called “best setup” to be the best? Are you considering fastest learning, most stable learning, or some other criteria that you choose to define?

#### Dataset
- Use the following environment from OpenAI Gym: [Pendulum Environment](https://www.gymlibrary.dev/environments/classic_control/pendulum/)
- **Note:** Stay within the older version of gym 0.17.3, as implemented in the lab for cartpole.

#### Submission Requirements for Part B:
1. Submit a zip file containing all the project files (source code, Jupyter notebook `.ipynb` file, `.html` file, best neural network weights `.h5`, slides).
2. Submit a `.docx` file containing the list of specific contributions by each team member in the deliverables for Part B.
3. Submit online via the Assignment link.
