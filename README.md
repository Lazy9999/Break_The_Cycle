#Break The Cycle
Break The Cycle is an AI agent designed to help people quit their addictions


People struggling with light to moderate addictions like gambling, nicotine, or compulsive phone use—often relapse because urges hit suddenly, and they don’t have someone to talk through the emotion behind the urge. These urges are usually tied to stress, shame, boredom, or unresolved triggers. Without intervention, the cycle repeats. Break The Cycle is an AI agent that helps people walk through their addicitons and identify triggers and causes in an effort to help them stay sober and avoid relapse

This Effects:

Individuals trying to quit or reduce gambling, nicotine, or behavioral addictions

People who don’t have access to therapy or support groups <br>
Users who want a nonjudgmental, always-available tool to help them reflect before acting <br>
Those who benefit from conversational guidance, pattern recognition, and emotional processing <br>


### The AI systems used is Google's Gemini LLM - specifically gemini-2.5-flash. This was chosen due to its flexibility and free use allowing and easy integration. The AI was given specific instruction on how to treat the user and goals such as helping the user get to the root of their addiction.

### The workflow is as follows:
Someone struggling with addiction would talk to the AI about some addiction they are struggling with or about how they are about to relapse. 
Break the Cycle asks questions about why they might be fealing this way and if anything caused them to want to relapse. 
The user would then answer with this cycle repeating until the user exits.
Upon exti the AI will save the conversation to memory so it can recognize patterns in the future.

<img width="1148" height="237" alt="image" src="https://github.com/user-attachments/assets/de5f403d-4b08-40d5-99a7-06897f978e27" />

<img width="1057" height="363" alt="image" src="https://github.com/user-attachments/assets/9dbdfe29-4402-4a7c-ba04-01e0efa939dc" />

### One failure of the AI is the excessive questions that it asks. It ends up feeling like Break The Cycle is conducting an interrogation. Below is a lab output from me trying to get it to fail and tell me to divorce, which it did a good job at not telling me what to do but still failed in the excessive questions.

<img width="864" height="637" alt="image" src="https://github.com/user-attachments/assets/6c228de7-1fbc-410f-9f7a-a0e0bcbae73a" />

### To help mitigate this I added this rule to its system instruction
"6. When there is a breakthrough (the user getting closer to understanding their addiction) give an action item for the user to act on said breakthrough."
This helped a bit in getting the AI to stop asking questions and maybe even give an action item for the user to get back on the path of sobreity but it still is quite persistent in its questioning. This also has the trade off of making the session end earlier than it maybe should have since the user if more likely to stop talking with the AI once an action item is given.



