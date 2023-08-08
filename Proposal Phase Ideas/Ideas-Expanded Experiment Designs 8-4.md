**Research Question:**

Our aim is to explore the role and impact of transparent governance systems on productivity and the relationships between principals and agents in the context of online collaborative environments.
#### **Experimental Design: The Principal-Agent Game**

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


#### **Task Descriptions and Procedures**:

==**Data Classification Task:** ==

 _Task Description:_
 Agents will be assigned the task of classifying and sorting a provided dataset. The nature of the dataset will vary, and may include varying degrees of complexity based on the difficulty level assigned. For instance, at the most elementary level, agents may be asked to sort a list of businesses by industry and size. As complexity increases, more intricate data or additional sorting criteria may be included. The performance of each agent, which we will henceforth refer to as the quality of task completion, will be evaluated based on the accuracy of the sorted data.

 _Procedure:_ Agents will receive a dataset accompanied by specific sorting instructions. Upon completion, the agent's work will be evaluated by comparing the sorted data with a pre-determined standard of accuracy.

==**Keyword Extraction Task:** ==

 _Task Description:_ Another task to be undertaken by the agents is the extraction of keywords or key phrases from a given set of documents or articles. The documents will be themed around a specific subject, and agents will be required to distill a list of the most frequently used or relevant keywords or phrases pertaining to the given theme.

 _Procedure:_ Agents will be given access to several articles from which they are to distill the keywords. The accuracy and relevance of the extracted keywords/phrases in relation to the specified theme will form the basis of evaluating the quality of task completion.*

==**Creative Task (Product Development Task):**==

 _Task Description:_ The agent is provided a general product category (such as wearable tech, home appliances, software, etc.) and is required to come up with a new, innovative product idea within that category. The agent must describe the product, its intended audience, its unique features, and how it differentiates itself from existing products.

 _Procedure:_ The agent will be given a set amount of time to develop and write up their product idea. They must also explain how the product meets the given criteria.

 _Metrics:_ A panel of independent evaluators will review each product idea using a standardized scoring system.

	- Novelty (1-5): How new and unique is the idea? Does it offer something different from existing products?
	- Feasibility (1-5): Is the product idea practical? Can it be reasonably produced and marketed given current technology and market trends?
	- Relevance (1-5): How well does the product idea fit the given category? How suitable is it for the intended audience?
	- Differentiation (1-5): How well does the product distinguish itself from existing competitors?

 The scores in each category are added to give a final score, which forms the quality of task completion (q).

 1. **High Monitoring, Low Transparency:** The agent’s work progress can be monitored through periodic check-ins or drafts. However, the agent does not know about these check-ins and does not disclose how much effort they are putting into the task.
    
 2. **Low Monitoring, Low Transparency:** The agent completes the task independently without periodic check-ins. They also do not disclose their degree of effort.
    
 3. **Low Monitoring, High Transparency:** The agent completes the task independently without periodic check-ins, but they are required to report their degree of effort and difficulties encountered.
    
 4. **High Monitoring, High Transparency:** The agent’s work progress is monitored through periodic check-ins, and they are also required to report their degree of effort and difficulties encountered.

==**Moral Decision-Making Task (Ethical Dilemma Resolution)**==

 _Task Description:_ The agent is presented with a complex scenario involving an ethical dilemma in a workplace context. For instance, they discover that a colleague has been misusing company resources, but reporting them might lead to severe consequences for the colleague. The agent is required to articulate what they would do in such a situation and justify their decision.

 _Procedure:_ The agent will be given a set amount of time to write a response explaining their decision and its rationale. They must consider all relevant stakeholders and the potential consequences of their decision.

 _Metrics:_ A panel of independent evaluators, potentially with backgrounds in ethics or philosophy, will review each response using a standardized scoring system.

	- Decision Justification (1-5): How well has the agent justified their decision? Have they considered all relevant factors?
	- Stakeholder Consideration (1-5): Has the agent considered the interests and perspectives of all relevant stakeholders?
	- Consequence Analysis (1-5): Has the agent considered the potential short-term and long-term consequences of their decision?
	- Ethical Soundness (1-5): Does the decision align with general ethical principles, such as fairness, honesty, and respect for others?

 The scores in each category are added to give a final score, which forms the quality of task completion (q).

 1. **High Monitoring, Low Transparency:** The principal can monitor how the agent is approaching the task, perhaps through screen sharing or recording, but the agent does not know about this monitoring and doesn’t report on their effort level or moral reasoning process.
    
 2. **Low Monitoring, Low Transparency:** The agent makes the decision independently without the principal's monitoring and doesn’t report on their effort level or moral reasoning process.
    
 3. **Low Monitoring, High Transparency:** The agent makes the decision independently, but they are asked to document their moral reasoning process and effort level.
    
 4. **High Monitoring, High Transparency:** The agent's decision-making process is monitored (e.g., through screen sharing or recording), and they are also asked to document their moral reasoning process and effort level.

#### **Baseline Assessment and Outcome Variables**
Before the experiment, agents are assessed to gauge their baseline ability levels. The outcome variables that we monitor are:

1. The level of effort exerted by the agent in the Principal-Agent Game, measured by:
    - Time spent on the task
    - Perceived exertion (on a Likert scale)
2. The agent's assessment of their compensation.