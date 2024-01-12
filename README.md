# Git Issue Reply Bot
AKA GIR

## Purpose
LLMs are pretty cool right? They can be used for customer service, they can answer questions about an API, and they can generate code.
So why dont we put them to work being the first responder on new issues created by our users?

## GIR Features
- Read new issues on your repo
- Determine if theres enough info to solve the issue
- Ask for more information if needed
- Determine if a fix is needed
- If no fix is needed, try to answer the question
- If a fix is needed, try to determine what should be done and generate a PR for review by the devs

## How to use
GIR should eventually be simple to install in a docker container, and configured to work with your repo with a yaml file.