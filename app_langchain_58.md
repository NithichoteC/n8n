n8n provides one Agent node, which can act as different types of agent depending on the settings you choose. Refer to the [Agent node documentation](/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.agent/index.md) for details on the available agent types.

When execute a workflow containing an agent, the agent runs multiple times. For example, it may do an initial setup, followed by a run to call a tool, then another run to evaluate the tool response and respond to the user.


-----------------------------------


# FILE: n8n-docs\docs\advanced-ai\examples\understand-chains.md


---
#https://www.notion.so/n8n/Frontmatter-432c2b8dff1f43d4b1c8d20075510fe4
title: What's a chain in AI?
description: Understand chains in the context of AI. Learn about chains in n8n.
contentType: explanation
---

# What's a chain in AI?

[Chains](/glossary.md#ai-chain) bring together different components of AI to create a cohesive system. They set up a sequence of calls between the components. These components can include models and [memory](/glossary.md#ai-memory) (though note that in n8n chains can't use memory).


## Chains in n8n

