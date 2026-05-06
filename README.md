# BrainLoop
BrainLoop -  An MCQ quiz tool using active recall &amp; spaced repetition. Answer correctly, and questions appear less often; answer wrong and they loop back sooner. Hard topics repeat until mastered, easy ones fade away. Small phases prevent overwhelm. Load your questions, start learning, and let your brain do the rest

'''How to Add Your Own Questions'''

##Ask any AI (ChatGPT, Claude, etc.) to format your questions using this template:
Generate MCQ questions in this format:
  {topic:"TOPIC_1_NAME",q:"QUESTION_1_TEXT?",options:["OPTION_A","OPTION_B","OPTION_C","OPTION_D"],answer:0,explanation:"EXPLANATION_FOR_Q1"},
  {topic:"TOPIC_1_NAME",q:"QUESTION_2_TEXT?",options:["OPTION_A","OPTION_B","OPTION_C","OPTION_D"],answer:1,explanation:"EXPLANATION_FOR_Q2"},
  {topic:"TOPIC_1_NAME",q:"QUESTION_3_TEXT?",options:["OPTION_A","OPTION_B","OPTION_C","OPTION_D"],answer:2,explanation:"EXPLANATION_FOR_Q3"},
  {topic:"TOPIC_1_NAME",q:"QUESTION_4_TEXT?",options:["OPTION_A","OPTION_B","OPTION_C","OPTION_D"],answer:3,explanation:"EXPLANATION_FOR_Q4"},

Paste your new questions from the AI between the brackets.

Save the file and open it in any browser. Your personalised quiz is ready — no installations, no coding required.


##COUNTER
Each question starts with a counter of 5. A correct answer decreases it by 1 (question appears less often), and a wrong answer increases it by 1 (question loops back sooner). When the counter hits 0, the question is considered mastered and removed from rotation.
![img alt](https://github.com/TANMAY-KARTIKAY/BrainLoop/blob/2d56c168807d810286b6ccbaac34402172750b7c/image.png)


##WRONG
If you answer a question wrong if will show the correct option with an explanation of why it's wrong and will add +1 to the count
![img alt](https://github.com/TANMAY-KARTIKAY/BrainLoop/blob/38525290c4ceb6b6c09d776782ce7b6380a36ce9/wrong.png)


##CORRECT
The selected option turns green, a checkmark (✓) appears, and the explanation is revealed to reinforce your understanding. The question's counter decreases by 1, meaning it will appear less frequently in future phases — you're closer to mastering it.
![img alt](https://github.com/TANMAY-KARTIKAY/BrainLoop/blob/67b266c09af128ca2e2d38d449af6068952ae4a0/CORRECT.png)

##NEXT PHASE
Once all 5 questions in the current phase are answered, the "Next Phase" button unlocks. Clicking it loads a fresh set of 5 random questions from your remaining unmastered pool, pushing you further toward completing all topics.
![img alt](https://github.com/TANMAY-KARTIKAY/BrainLoop/blob/67b266c09af128ca2e2d38d449af6068952ae4a0/NEXT%20PHASE.png)

#How It Works

1. The Counter System
Each question starts with a counter of 5. Answer correctly and the counter drops by 1 — that question appears less often. Answer wrong and the counter rises by 1 — it loops back sooner. When the counter hits 0, the question is marked as mastered and removed from rotation. Hard topics keep coming back; easy ones fade away.

2. The Phase System
Questions are served in phases of 5 random questions drawn from your unmastered pool. Answer all 5 to unlock the "Next Phase" button, which loads a fresh set. This bite-sized approach prevents overwhelm and gives you a clear sense of progress with every phase completed.

3. The Loop
Wrong answers increase the counter → questions reappear → you try again → you improve → the counter drops → you master it. This continuous loop ensures you spend time where it matters most — on the topics you haven't fully grasped yet.
