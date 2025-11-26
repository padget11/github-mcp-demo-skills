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

### **Phase 2: Create Hotfix Branch** 🌿

**🌱 Strategic Branching: Implementing Best Practices**

Guide AI through proper branching strategy for hotfixes. This demonstrates professional development workflows and Git best practices.

**What this phase achieves**: Creates a dedicated hotfix branch following naming conventions, preparing for isolated bug fix development.

**User Prompt:**
```
Now let's create a hotfix branch to fix this CSS issue. Can you create a branch called 'hotfix/css-stylesheet-typo' and switch to it?
```

**Expected AI Actions:**
- Create hotfix branch with descriptive name
- Switch to the new branch for development
- Confirm branch creation and current working branch

### **Phase 3: Local Development & Fix** 🛠️

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

### **Phase 4: Push & Create PR** 📤

**🚀 Collaborative Review: Preparing Changes for Integration**

Guide AI through committing changes and creating a pull request for code review.

**What this phase achieves**: Demonstrates proper commit practices and PR creation, setting up the review process.

**User Prompt:**
```
Great! The fix looks good. Now let's commit this change and push it to create a PR. Use a descriptive commit message about fixing the CSS stylesheet typo.
```

**Expected AI Actions:**
- Stage and commit changes with descriptive message
- Push the hotfix branch to remote repository
- Use `mcp_github_create_pull_request` to create PR
- Set appropriate title and description for the PR