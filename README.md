# Personal AI Employee - Hackathon 0

## Overview
This project was developed for **Hackathon 0**, where the challenge was to create a **Personal AI Employee** capable of handling tasks like emails, WhatsApp messages, and file management, while maintaining human approval.  

I completed the challenge using **Obsidian** as my knowledge base and workspace, along with **Claude Code** for AI task planning and execution.

---

## Hackathon 0 Tasks & Completion
The Hackathon 0 required completing the following tasks:

1. **Task Detection**: Monitor incoming emails, WhatsApp messages, and new files.  
   - ✅ **Completed in Obsidian**: All incoming tasks were organized into a `/Needs_Action` folder.
   
2. **Task Planning**: Generate a structured plan for each task.  
   - ✅ **Completed using Claude Code**: AI suggested steps for each task, saved in `/Plans` in Obsidian.

3. **Human Approval**: Ensure critical tasks are verified before execution.  
   - ✅ **Completed in Obsidian**: Tasks awaiting approval were moved to `/Pending_Approval`.  
   - Humans approved tasks directly in Obsidian before execution.

4. **Task Execution**: Perform the task after approval.  
   - ✅ **Completed using Claude + scripts**: Once approved, Claude Code triggered execution scripts (emails sent, files organized, WhatsApp responses sent).

5. **Completion Tracking**: Keep record of completed tasks.  
   - ✅ **Completed in Obsidian**: Completed tasks were moved to `/Done` folder, creating a clear history and dashboard of activities.

---
[Incoming Tasks]
        
        
  
  │ Needs_Action  │  <-- New emails, WhatsApp, files
  
        
        
  
  │     Plans     │  <-- Claude generates step-by-step plan
  
        
        
  
  │ Pending_Approval │  <-- Human approves before execution
  
        
        
  
  │      Done     │  <-- Completed tasks, history tracked
  



## Tools & Technologies
- **Obsidian**: Knowledge base, task dashboard, folder workflow (`Needs_Action`, `Plans`, `Pending_Approval`, `Done`)  
- **Claude Code**: AI task planning and execution  
- **Python**: Scripts for watching emails, WhatsApp, and file system  
- **Git/GitHub**: Version control  

---

## Summary
By combining **Obsidian** and **Claude Code**, I implemented a **human-in-the-loop AI assistant** that automatically detects, plans, approves, executes, and tracks tasks — fully completing the requirements of Hackathon 0.


