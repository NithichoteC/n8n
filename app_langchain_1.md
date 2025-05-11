👉 Learn more about configuring the [HTTP Request tool](/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.toolhttprequest.md).


### Scoped API keys
Users on the Enterprise plan can now create API keys with specific scopes to control exactly what each key can access.

<figure markdown="span">
    ![Scoped API keys](/_images/release-notes/scoped-API-keys.png)
    <figcaption>Scoped API keys</figcaption>
</figure>

Previously, API keys had full read/write access across all endpoints. While sometimes necessary, this level of access can be excessive and too powerful for most use cases.  Scoped API keys allow you to limit access to only the resources and actions a service or user actually needs.

**What’s new**

When creating a new API key, you can now:

- Select whether the key has read, write, or both types of access.  
- Specify which resources the key can interact with.  

Supported scopes include:

- Variables — list, create, delete  
- Security audit — generate reports  
- Projects — list, create, update, delete  
- Executions — list, read, delete  
- Credentials — list, create, update, delete, move  
- Workflows — list, create, update, delete, move, add/remove tags  

Scoped API keys give you more control and security. You can limit access to only what’s needed, making it safer to work with third parties and easier to manage internal API usage.

### Drag and Drop in Folders

Folders just got friendlier. With this release, you can now **drag and drop workflows and folders** — making it even easier to keep things tidy.

Need to reorganize? Just select a workflow or folder and drag it into another folder or breadcrumb location. It’s a small change that makes a big difference when managing a growing collection of workflows.

<br>
<video src="/_video/release-notes/Drag-and-drop-folders.mp4" controls width="100%"></video>
<br>

📁 Folders are available to all [registered](/hosting/community-edition-features.md#registered-community-edition) users—jump in and get your workspace in order!

### Contributors

[Zordrak](https://github.com/Zordrak){:target=_blank .external-link}  

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.89.2

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.89.1...n8n@1.89.2){:target=_blank .external-link} for this version.<br />
**Release date:** 2025-04-16

This release contains a bug fix.

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.89.1

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.89.0...n8n@1.89.1){:target=_blank .external-link} for this version.<br />
**Release date:** 2025-04-15

This release contains bug fixes.

For full release details, refer to [Releases](https://github.com/n8n-io/n8n/releases){:target=_blank .external-link} on GitHub.

## n8n@1.89.0

View the [commits](https://github.com/n8n-io/n8n/compare/n8n@1.88.0...n8n@1.89.0){:target=_blank .external-link} for this version.<br />
**Release date:** 2025-04-14

