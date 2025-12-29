# To Agent or Not to Agent: That Is Most Likely Not the Right Question [ DRAFT-DO-NOT-READ]

This is my initial exploration and reflections of the initial chapters of the D Design Multi Agent Systems book, so far
surpassing my expectations on quality.

## When you probably don't need it ? 

1. You really don't know what AI Agents are you see the pressure building up on your socials.

2. Your problem  and solution are deterministic
    - Calculating BMI , KPI's
    - Identifying the shortest route between 2 places
    - Querying a database for specific information
    - Process a file with known structure
      
3. The cost of using an Agentic system surpasses the value you provide by your service

## When you might consider it:

1. Your problem is non deterministic and failures are well tolerated within the business context

2. You have exhausted all the state of the arts techniques and you still can't solve your problem end to end completely
   
3. LLM's provide great results to parts of your problem and you think there is a chance for an end to end solution

## Taxonomy of Agentic Systems

- LLM + Prompts
This is what you generally do , with your traditional LLM's and prompt operations , it can get you very far and reduce turn around time on a lot of knowledge based tasks.

- Single Agents
This systems are systems that require the use of an underlying LLM's models and actually can use tools that are available in the Ecosystem. 

- Multi Agent Systems
This envolves many agents coordination and a level consistency there are definitely many kind of orchestration based systems on this case.
