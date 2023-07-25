- Action item: 
	- Keep looking at experiment design
	- Propose concrete experimental design
	- Concrete research question
	- Find existing lit in the field on online work

Research Question:

Our aim is to explore the role and impact of transparent governance systems on productivity and the relationships between principals and agents in the context of online collaborative environments.

**Experimental Design: The Principal-Agent Game**

The experiment design utilizes a game theoretic approach involving two roles: the principal and the agent. The game aims to mimic real-world scenarios where the principal (the experimenter) engages agents to perform an array of non-trivial tasks, such as data sorting and keyword distilling.

In each round of the game, the principal has private information, such as details about the monitoring technology in use and the degree of task difficulty, which is either conceal or disclose to the agent (depending on randomly chosen game states). Conversely, the agent reveals or withholds private information pertaining to the effort required to accomplish the task, such as the expected time to task completion.

The game introduces a variety of transparency and monitoring conditions under which the principal-agent interaction can occur:

1. **High Monitoring, Low Transparency:** The principal can monitor all aspects of the agent's work, such as the time taken to complete the task. The agent, however, is unaware of the monitoring technology and does not disclose their degree of effort.
    
2. **Low Monitoring, Low Transparency:** Neither the principal nor the agent can monitor the other's activities. Furthermore, the agent does not disclose the degree of effort.
    
3. **Low Monitoring, High Transparency:** The principal cannot monitor the agent's work, but the agent is aware of the principal's monitoring capabilities and discloses their degree of effort.
    
4. **High Monitoring, High Transparency:** The principal can monitor all aspects of the agent's work and the agent is aware of this monitoring. Additionally, the agent discloses their degree of effort.


| | High Monitoring | Low Monitoring |  
| -------: | :------: | :------ |  
| **High Transparency**| Principal Monitors Agent, Agent Aware of Monitoring, Agent Disclose Difficulty| Principal Doesn't Monitors Agent, Agent Aware of Monitoring, Agent Disclose Difficulty|  
| **Low Transparency** | Principal Monitors Agent, Agent Unaware of Monitoring, Agent Doesn't Disclose Difficulty| Principal Doesn't Monitors Agent, Agent Unaware of Monitoring, Agent Doesn't Disclose Difficulty|



**Reward System**

To simulate real-world incentives, we introduce a reward system. The principal starts with 50 points and must allocate some of these points as a reward for each task assignment. The agent can then choose to accept or decline the task based on their evaluation of the reward.

The principal's reward depends on the quality of work submitted by the agent, as determined by these factors:

- Quality of Task Completion (q), represented by 1.5 multiplied by the percentage accuracy.
- Task Difficulty (t), with three tiers (easy, medium, hard) represented by multipliers 1.1, 1.2, and 1.5, respectively.

The agent's reward from each session is based on the initial pay set by the principal.

The reward function for each party is as follows:

- Principal's Reward (r(p)) = assignment quantity * t * q
- Agent's Reward (r(a)) = assignment price

This game is repeated for 'n' rounds. After each round, the agent makes a private assessment of the task's difficulty and has the option to express concerns regarding the task bounty.

**Task Descriptions and Procedures**

1. **Data Classification Task:** Agents will be assigned the task of classifying and sorting a provided dataset. The nature of the dataset will vary, and may include varying degrees of complexity based on the difficulty level assigned. For instance, at the most elementary level, agents may be asked to sort a list of businesses by industry and size. As complexity increases, more intricate data or additional sorting criteria may be included. The performance of each agent, which we will henceforth refer to as the quality of task completion, will be evaluated based on the accuracy of the sorted data.
    
    _Procedure:_ Agents will receive a dataset accompanied by specific sorting instructions. Upon completion, the agent's work will be evaluated by comparing the sorted data with a pre-determined standard of accuracy.
    
2. **Keyword Extraction Task:** Another task to be undertaken by the agents is the extraction of keywords or key phrases from a given set of documents or articles. The documents will be themed around a specific subject, and agents will be required to distill a list of the most frequently used or relevant keywords or phrases pertaining to the given theme.
    
    _Procedure:_ Agents will be given access to several articles from which they are to distill the keywords. The accuracy and relevance of the extracted keywords/phrases in relation to the specified theme will form the basis of evaluating the quality of task completion.**

**Baseline Assessment and Outcome Variables**

Before the experiment, agents are assessed to gauge their baseline ability levels. The outcome variables that we monitor are:

1. The level of effort exerted by the agent in the Principal-Agent Game, measured by:
    - Time spent on the task
    - Perceived exertion (on a Likert scale)
2. The agent's assessment of their compensation.

