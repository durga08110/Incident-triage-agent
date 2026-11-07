# Incident-triage-agent
This is an AI agent built using LangGraph for automating RCA on application issues sent as alerts from Dynatrace<br>
Components: LangGraph, AWS API Gateway, AWS Lambda, SQS, Bedrock,Hybrid RAG,Langsmith,Slack with Human approval for further actions <br><br>
When alerts are triggered from Dynatrace, developers spend time:<br>
a. Analyzing logs<br>
b. Searching for similar past issues <br>
c. Checking recent commits <br>

The goal is to automate this RCA and finally give developers full control over how to proceed.<br>





![architecture diagram](architecture.svg)
