## Q&A over SQL database

A project to build a question and answer system over SQL database using natural language prompt. This allows a user to ask questions about structured data contained in databases without using SQL queries.

Concepts used in the project:
- Sql agent
- Retrievers as tools - used to help the LLM to create the sql query accurately
- Few-shot prompting - use of example sql queries as reference for the LLM to construct the SQL query
- Chain of thought prompting - to guide the agent in its reasoning steps to take
- LangChain as framework
