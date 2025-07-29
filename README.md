# mini-AI-Safety-Via-Debate

Set up a mini “AI safety via debate” scenario to explore if multiple AIs 
can help catch each other’s mistakes. For example, pick a difficult question (factual or a tricky 
riddle) and have two instances of an LLM debate the answer. One instance argues for a correct 
answer while another subtly argues for an incorrect answer. As the human judge, see if the 
debate makes it easier to tell which answer is more truthful. This exercise illustrates the Debate 
approach to scalable oversight (where AIs argue and a human judges truthfulness). You can do 
this in a notebook by prompting GPT-4 (or another model) in a loop: alternate turns between a 
“Pro” agent and a “Con” agent. After a few back-and-forth exchanges, evaluate which side is 
more convincing and correct. Did the debate surface relevant evidence or logic that a single 
answer might have missed? This will give you hands-on insight into the strengths and limits of 
debate as an oversight technique (e.g. does a persuasive lie sometimes beat the truth?). Feel 
free to be creative – try domains like logic puzzles or technical questions – and see if the truthful 
argument reliably wins (a key assumption for debate to work). To take it one step further, 
implement an LLM judge to replace your human judgement and see if it’s able to reliably select 
the truthful argument. 
