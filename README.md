# Troubleshooting Question

## The Idea

A very common interview question is to ask you to troubleshoot an imaginary issue.  Anything from servers losing contact with the moon to "my friend that had a customer complaining about our website's buttons" (read: they just solved this problem last week and want to see how you'd solve it.

Like most interview questions, there is no "right answer" to this type of question.  The interviewer is trying to see how you would react in a stressful environment with ambiguity and uncertainty.  What tools do you have in your toolbelt?  What happens when you're outside of your comfort zone?

## The Prompt

>**Interviewer**: You've been working in a dev shop for a couple weeks.  You know some basic things about your product, but are not terribly familiar with the code itself.  In this hypothetical dev shop, there is a phone where customers can complain about issues they're having with the software, and the company rotates which developer has to man this phone.  You drew the short straw, so it's your turn.  The phone rings, and you pick it up...

The rest of the prompt is ad-libbed.  An interviewer will invent a customer's problem with the site.  The interviewee must describe how they would solve this problem, step-by-step.

## Strategies for the Interviewee

- Never give up.  There is no such thing as "that's the last thing I could do", dig deeper.
- Be honest about your skills.  Don't pretend you know exactly what the log files would be called on this imaginary server you just connected to.  "I'm pretty sure they would be in this folder, but I can't remember exactly what they're called," is a perfectly OK response.
- It's OK to talk out a solution from vague to specific.  "I would log into the server," may be good enough for the interviewer vs "I would use SSH to connect on port 22 and I would use a public key".  The interviewer will probably ask you if more specifics are needed, and while you're talking, a more clear plan of attack may present itself.
- Write/draw things out.  If there is a whiteboard available, diagrams will clarify your approach to the interviewer, and to yourself.

## Strategies for the Interviewer

- Think back to all the problems you've ever encountered.  
  - How did they manifest themselves?  Server down?  CSS not updating properly?  
  - How did you narrow down the issue?  Dev tools?  Terminal?  Stackoverflow?  Ask a friend?
  - You have seen hundreds of issues in this program.  You just need enough to fill 10 minutes.
- Be honest about **your** skills.  Don't invent issues you don't know at least one way to solve.
- Don't give it up too easily.  If possible, have the interviewee check a few paths before they "resolve" the issue / look in the "right place".
