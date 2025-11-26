### **Phase 1: Issue Discovery** 🔍

**🕵️ Guided Investigation: Teaching AI to Analyze Problems**

Direct your AI assistant to investigate the styling issue. This demonstrates how to guide AI through problem analysis and root cause identification.

**What this phase achieves**: Shows how to prompt AI for technical investigation while maintaining human oversight of the discovery process.

**User Prompt:**
```
Copilot, I just opened my World Clock website and it looks completely broken - all the beautiful styling is missing and it's just plain HTML. Can you investigate what's wrong with the styling?
```

**Expected AI Actions:**
- Analyze HTML file for CSS link issues
- Identify the typo in `href="styls.css"`
- Explain the root cause and impact

### **Phase 2: Issue Management via GitHub MCP** 📝

**📝 Collaborative Bug Tracking: Using MCP Tools for Issue Management**

Demonstrate how to use GitHub MCP tools for creating and managing issues directly from VS Code. This shows the power of integrated workflows.

**What this phase achieves**: Creates a GitHub issue using MCP tools, demonstrating seamless integration between development environment and project management.

**User Prompt:**
```
Now that we've found the CSS link typo, can you create a GitHub issue to track this bug? Make it a critical priority since it breaks the entire user experience. Please create the issue against the current demo branch (not main).
```

**Expected AI Actions:**
- Use `mcp_github_create_issue` to create bug report
- Include detailed description of the CSS link typo
- Set appropriate labels (bug, critical) and priority
- Reference the specific file and line number
- Link to demo branch context

### **Phase 3: Create Hotfix Branch** 🌿

**🌱 Strategic Branching: Implementing Best Practices**

Guide AI through proper branching strategy for hotfixes. This demonstrates professional development workflows and Git best practices.

**What this phase achieves**: Creates a dedicated hotfix branch following naming conventions, preparing for isolated bug fix development.

**User Prompt:**
```
Perfect! Now let's create a hotfix branch to fix this CSS issue. Can you create a branch called 'hotfix/css-stylesheet-typo' and switch to it?
```

**Expected AI Actions:**
- Create hotfix branch with descriptive name
- Switch to the new branch for development
- Confirm branch creation and current working branch

### **Phase 4: Local Development & Fix** 🛠️

**🔧 Guided Code Repair: AI-Assisted Bug Resolution**

Direct AI to implement the actual fix while maintaining human oversight of the changes. This shows collaborative development practices.

**What this phase achieves**: Fixes the CSS link typo with AI assistance, demonstrating how to guide AI through specific code changes.

**User Prompt:**
```
Now let's fix the actual bug. Can you correct the CSS link in index.html from 'styls.css' to 'styles.css'? Please show me the change you're making.
```

**Expected AI Actions:**
- Locate the incorrect CSS link in index.html
- Make the correction: `href="styls.css"` → `href="styles.css"`
- Show the diff/change being made
- Verify the fix is applied correctly