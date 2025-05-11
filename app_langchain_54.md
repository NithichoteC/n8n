This workflow uses the [Chat Trigger](/integrations/builtin/core-nodes/n8n-nodes-langchain.chattrigger/index.md) to provide the chat interface, and the [Call n8n Workflow Tool](/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.toolworkflow.md) to call a second workflow that handles checking for email addresses and sending the Slack message. 

[[ workflowDemo("file:///advanced-ai/examples/ask_a_human.json") ]]

## Key features

This workflow uses:

