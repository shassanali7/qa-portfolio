## Bug: Project Image Removed After Edit

# Module
Project Management

# Platform
Web

# Description
When editing a project and updating details, existing project images are removed unintentionally.

# Steps to Reproduce
1. Open a project with images
2. Click Edit
3. Update any field (without changing image)
4. Save changes

# Expected Result
- Existing images should remain unchanged unless explicitly modified

# Actual Result
- Project images are removed after update

# Severity
Major

# Priority
High

# Impact
- Data loss (images)
- Affects project presentation

# Notes
Likely issue with update API not retaining existing media