# Incident-triage-agent
This is an AI agent built using LangGraph for automating RCA on application issues sent as alerts from Dynatrace<br>
Components: LangGraph, AWS API Gateway, AWS Lambda, SQS, Bedrock,Hybrid RAG,Langsmith,Slack with Human approval for further actions <br><br>
When alerts are triggered from Dynatrace, developers spend time to:<br>
a. Analysing logs<br>
b. Search for any similar issues that occurred in the past <br>
c. Check recent commits <br>

The aim is to automate this RCA and finally give the control to the developers to decide how to proceed.<br>





![architecture diagram](architecture.svg)
