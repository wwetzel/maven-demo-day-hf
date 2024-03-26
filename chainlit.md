🤖💼 Exit Survey Sage 🤖💼 - Your go-to guru 🧙‍♂️📚 for all things quit-tastic! 🚪🏃‍♀️💨 Ask away and dive deep into the why's of goodbye's 🤔👋! 🌪️🔥 Whether it's data drama 📈🎭 or insights with attitude 😎📉, I'm here to spice up your analysis! 🌶️💡 Let's decode 🕵️‍♂️🔍 the secrets behind those exit doors! 🚪🔓


This is an Agent🤖 which will query employee exit survey data and answer questions about it. The Agent has access to the following data:

a. 1k synthetically generated employee exit surveys
b. The data has the following columns

Term Year | Term Month | Job Title | Business Unit | Gender | main_quit_reason_text | main_quit_reason_text_sentiment | nps

Some example data
```
Term Year: 2022
Term Month: 1	
Job Title: superintendent 2
Business Unit: business unit E
Gender: male
main_quit_reason_text: I felt pigeonholed into a specific role at ABC company with no room for growth or exploration of other areas within construction. The company culture also did not align with my values.	
main_quit_reason_text_sentiment: Negative
nps: 6

Term Year: 2019
Term Month: 2
Job Title: superintendent 2
Business Unit: business unit A
Gender: female
main_quit_reason_text: I loved working on the diverse range of projects at ABC company and will miss my colleagues. However, a once-in-a-lifetime opportunity has come up for me elsewhere, which aligns more closely with my career goals.
Positive
nps: 3

```

The Agent has access to the following tools:
a. Database query tool - The above 1k records is accessible to the agent via a sqlite database.
b. Vector database retriever tool - The main_quit_reason_text has been embedded and loaded into a ChromaDB instance, this is available to the agent for RAG.
c. Python REPL tool. The Agent can run Python code and retrieve the results, it can also do plotting of query results.

