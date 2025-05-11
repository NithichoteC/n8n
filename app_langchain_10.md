- [Anthropic Chat Model](/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmchatanthropic.md): Added support for claude-3-5-sonnet-20241022  

We made updates to how projects and workflow ownership are displayed making them easier to understand and navigate. 

We further improved the performance logic of partial executions, leading to a smoother and more enjoyable building experience. 

### New n8n canvas alpha
We have enabled the alpha version of our new canvas. The canvas is the ‘drawing board’ of the n8n editor, and we’re working on a full rewrite. Your feedback and testing will help us improve it. 
[Read all about it on our community forum](https://community.n8n.io/t/help-us-test-the-new-n8n-canvas-alpha/60070). 


For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.65.2

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.65.1...n8n@1.65.2){:target=_blank .external-link} for this version.<br />
**Release date:** 2024-10-28

This release contains bug fixes.

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.64.3

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.64.2...n8n@1.64.3){:target=_blank .external-link} for this version.<br />
**Release date:** 2024-10-25

This release contains bug fixes.

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.65.1

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.65.0...n8n@1.65.1){:target=_blank .external-link} for this version.<br />
**Release date:** 2024-10-25

This release contains bug fixes.

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.65.0

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.64.1...n8n@1.65.0){:target=_blank .external-link} for this version.<br />
**Release date:** 2024-10-24

/// warning | [Breaking change](https://github.com/n8n-io/n8n/blob/master/packages/cli/BREAKING-CHANGES.md){:target=_blank .external-link}
What changed?
Queue polling via the environment variable `QUEUE_RECOVERY_INTERVAL` has been removed.

When is action necessary?
If you have set `QUEUE_RECOVERY_INTERVAL`, you can remove it as it no longer has any effect.
///

