# Guidelines for Creating an Issue

## 1. Labeling
- Prefix-based labels (e.g., `Target: Frontend`, `Target: Backend`, `Target: Mobile`) are **exclusive** within their category. This means a single ticket should not have more than one `Target` label.
- If you feel the need for multiple labels from the same prefix (e.g., both `Target: Frontend` and `Target: Backend`), it indicates that the issue should likely be split into multiple tickets. For example:
  - One ticket for `Target: Frontend`
  - Another for `Target: Backend`

## 2. Templates
- Always use the provided issue templates. These templates are continuously improved based on team feedback, and using them ensures consistency and streamlines the issue-creation process.

## 3. Issue Titles
- Including emojis and keywords (e.g., `✅ Feature`) in the title enhances readability. However, **this does not replace the use of labels**. For example, while `✅ Feature` in the title is helpful, you must still assign the corresponding label like `Type: Feature` to maintain proper categorization.

---

# Contributing to the Issue

## 1. Branch & Commit Naming
- When naming a branch, always include the issue ID that the branch is linked to. For example: `1-create-event`. 
- Similarly, ensure commit messages are descriptive and reference the issue, like this example: `#1 Convert event flow to steppers`. This practice helps automatically link the branch and pull request to the corresponding issue.

## 2. Manually Linking the Issue
- After creating a branch, you can manually link it to an issue by navigating to the issue page. In the right-hand sidebar, under the `Development` section, you can link the branch to the issue to create a direct association.
