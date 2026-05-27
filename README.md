# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 
ChatGPT
Python (Optional for implementation)
VS Code / Google Colab / Command Prompt Interface

# Explanation: 
The objective of this experiment is to design a Personal Productivity Assistant powered by an LLM such as OpenAI ChatGPT.
The assistant interacts with users using natural language prompts and performs productivity-related tasks like task management, scheduling, reminders, wellness recommendations, and answering general queries.

The application demonstrates how prompt engineering can progressively improve the assistant’s intelligence and usability.

# Problem Statement
Design a personal productivity assistant that can:
Manage daily tasks
Schedule reminders
Suggest wellness tips
Answer general user queries
Adapt to changing user preferences over time
The assistant should communicate naturally and provide user-friendly responses.

# Procedure
Step 1: Define Core Requirements
The assistant should include:
Task management
Reminder scheduling
Wellness guidance
General question answering
Basic memory/preference adaptation

Step 2: Construct Prompt Designs
Prompt 1 – Basic Task Reminder
Prompt:
Remind me to complete my AI assignment at 7 PM.
Output:
Sure! I will remind you to complete your AI assignment at 7 PM today.

Prompt 2 – Daily Task Organization
Prompt:
Organize my tasks for today:
1. Finish lab record
2. Attend online class at 2 PM
3. Buy groceries
4. Go for exercise
Output:
Today's Schedule:
High Priority:
• Finish lab record
• Attend online class at 2 PM
Medium Priority:
• Buy groceries
Personal Wellness:
• Go for exercise

Prompt 3 – Smart Scheduling
Prompt:
Schedule a meeting at 4 PM and check whether I have any conflicts.
Output:
You already have a study session scheduled from 3:30 PM to 4:30 PM.
Suggested Options:
• Move meeting to 5 PM
• Reschedule study session

Prompt 4 – Wellness Suggestion
Prompt:
Suggest wellness tips for someone working on a computer for long hours.
Output:
Wellness Tips:
• Drink water every hour
• Take a 5-minute eye break every 30 minutes
• Stretch your neck and shoulders regularly
• Avoid excessive screen brightness

Prompt 5 – Adaptive Assistant Prompt
Prompt:
I prefer studying at night and exercising in the morning. Organize my routine accordingly.
Output:
Personalized Daily Routine:
Morning:
• Exercise from 6 AM – 7 AM
Afternoon:
• Attend classes and complete light tasks
Night:
• Dedicated study session from 8 PM – 11 PM

# Sample Python Implementation
```
print("=== Personal Productivity Assistant ===")

while True:
    user = input("You: ")

    if "task" in user.lower():
        print("Assistant: Your task has been added successfully.")

    elif "remind" in user.lower():
        print("Assistant: Reminder scheduled.")

    elif "wellness" in user.lower():
        print("Assistant: Drink enough water and take regular breaks.")

    elif "exit" in user.lower():
        print("Assistant: Goodbye!")
        break

    else:
        print("Assistant: I can help manage tasks and reminders.")

```
# Features of the Productivity Assistant
## 1. Daily Task Manager
Accepts tasks in natural language
Organizes tasks by priority
Displays pending activities
## 2. Smart Scheduler
Schedules reminders and meetings
Detects time conflicts
Suggests better schedules
## 3. Wellness Recommendation System
Provides health and productivity tips
Suggests breaks and exercise routines
Encourages healthy digital habits
## 4. Adaptive Response System
Learns user preferences
Adjusts schedules dynamically
Provides personalized suggestions
# Advantages
Easy natural language interaction
Improves personal productivity
Reduces manual scheduling effort
Personalized user experience
Flexible and scalable system
# Applications
Student daily planning
Office productivity management
Personal wellness tracking
Smart virtual assistant systems
Time management applications

# Expected Output
The system successfully accepts user prompts and generates meaningful productivity assistance such as:
Task reminders
Schedule management
Wellness recommendations
Personalized routine suggestions
The assistant interacts naturally and adapts based on user preferences.


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
