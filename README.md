 EXPRIMENT-7
NAME:S DHARSHAN
REG NO:212222040036
Developing a Prompt-Based Application
for Daily Task Organization Using
ChatGPT
With the rapid advancements in large language models (LLMs), such as ChatGPT,
there is an exciting opportunity to develop prompt-based applications that enhance
creativity and practical problem-solving skills. This document demonstrates how to
create a prompt-based application tailored for organizing daily tasks. We explore a
progression from simple to advanced prompt designs and showcase their
corresponding outputs.
1. Introduction to Prompt-Based Applications
Prompt-based applications rely on carefully crafted inputs (prompts) given to language
models like ChatGPT to produce useful outputs. These applications can automate,
augment, and optimize tasks in various domains.
Organizing daily tasks is a practical problem many face. Using prompt-based solutions
can help individuals plan, prioritize, and review their workflows efficiently.
2. Objective
To build a prompt-based application using ChatGPT that:
• Allows users to input their daily tasks.
• Generates an organized and prioritized daily plan.
• Provides suggestions for improving productivity.
• Demonstrates advancement from simple to complex prompt designs.
3. Prompt Designs and Examples
3.1 Simple Prompt Design
The simplest prompt allows users to input a list of tasks for the day, and ChatGPT
outputs a basic, unordered task list.
User input:
"Here are my tasks for today:
- Buy groceries
- Finish the report
- Call Alice
- Workout"
Prompt to ChatGPT:
"Please list the following tasks in a simple bullet format without any
prioritization."
ChatGPT output:
- Buy groceries
- Finish the report
- Call Alice
- Workout

3.2 Intermediate Prompt Design: Task Prioritization
To make the application more useful, the prompt can ask ChatGPT to organize tasks
based on urgency and importance.
Prompt to ChatGPT:
"Given the following tasks, please categorize and prioritize them into High,
Medium, and Low priority based on typical urgency and importance."
User input:
- Buy groceries
- Finish the report (due tomorrow)
- Call Alice (to discuss weekend plans)
- Workout
ChatGPT output:
High Priority:
- Finish the report (due tomorrow)
Medium Priority:
- Buy groceries
Low Priority:
- Call Alice (to discuss weekend plans)
- Workout

3.3 Advanced Prompt Design: Time Management and
Recommendations
At the most advanced level, the prompt encourages ChatGPT not only to prioritize but
also to allocate time slots and suggest productivity techniques.
Prompt to ChatGPT:
"Using the tasks listed, create a daily schedule allocating approximate time
durations and include productivity tips for each task."
User input:
- Finish the report (due tomorrow, estimated time: 3 hours)
- Buy groceries (1 hour)
- Call Alice (30 minutes)
- Workout (1 hour)
ChatGPT output:
9:00 AM - 12:00 PM: Finish the report
Tip: Use the Pomodoro technique to maintain focus with 25-minute intervals
and 5-minute breaks.
12:00 PM - 1:00 PM: Buy groceries
Tip: Create a shopping list beforehand to avoid unnecessary browsing.
1:00 PM - 1:30 PM: Call Alice
Tip: Prepare key points to discuss to keep the call concise.
1:30 PM - 2:30 PM: Workout
Tip: Combine cardio and strength exercises for best use of time.

4. Application Development Framework
To implement the application, the workflow includes:
1. User Interface: A simple input form allowing users to list tasks and select the
desired complexity level (Simple, Intermediate, Advanced).
2. Prompt Construction: Based on user selection, construct the corresponding
prompt dynamically incorporating the user's task list.
3. Interaction with ChatGPT API: Send the constructed prompt and retrieve
responses.
4. Output Presentation: Display the output clearly with categories, time slots, or
recommendations as returned by the model.
5. Study Table: Comparison of Prompt Designs
Aspect Simple Prompt Intermediate Prompt Advanced Prompt
Input List of tasks List of tasks +
instructions to prioritize
List of tasks + time estimates +
scheduling request
Output Unordered
task list
Tasks categorized by
priority
Timed schedule + productivity
tips
Complexity Low Medium High
User
Benefit
Basic
organization
Improved prioritization Complete time management
and productivity guidance
6. Example Application Usage
Consider a user named Emma who wants to organize her tasks. Below are screenshots
demonstrating the app in action:
Figure 1: Simple prompt output showing unordered task list.Figure 2: Intermediate
prompt output with prioritized tasks.Figure 3: Advanced prompt output with daily
schedule and productivity tips.
7. Benefits and Practical Implications
Developing prompt-based applications with ChatGPT offers several advantages:
• Enhances Creativity: Users can experiment with different prompt styles for
customized outputs.
• Practical Problem-Solving: Provides structured solutions to common
organizational problems.
• Scalability: Easily expandable to other domains such as project management or
study planning.
• User Empowerment: Encourages users to reflect on their tasks and improve
productivity.
8. Conclusion
This demonstration showed how to leverage ChatGPT’s capabilities to build a promptbased application tailored for organizing daily tasks. By gradually enhancing prompts
from simple listings to detailed schedules with personalized recommendations, users
gain increasing value and practical assistance. The modular nature of prompt design
ensures adaptability to varied personal needs, fostering creativity and effective problemsolving.
Future enhancements could include integrating calendar APIs, real-time collaboration
features, or voice inputs, further enriching the user experience and organizational
efficiency.
