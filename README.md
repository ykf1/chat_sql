# qna_sql

A project to build a question and answer system over SQL database using natural language prompt. This allows a user to ask questions about structured data contained in databases without using SQL queries.

Concepts used in the project:
- Sql agent
- retrievers as tools - used to help the LLM to create the sql query accurately
- few-shot prompting - use of example sql queries
- chain of thought prompting - enable agent to reason step by step
