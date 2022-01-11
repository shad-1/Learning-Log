# Personal Rules
### A Programmer's guide to avoid breaking everything, primarily from experience breaking things. Intended for an audience of one, may be useful to more. 

### When merging a feature...
- Always be positive you are merging __all__ involved branches. 
    - __**Do not** count on the workflow management tool to accurately report which branches are involved__.
- **Do not** merge at the end of shift.
- **NEVER** merge right before the weekend.

### When reviewing code...
- If it is a **SQL migration**, check for hardcoded database references. Different environments will likely have different database names. Reference tables instead.

### When Planning a Story...
- Consider possible regressions.
- Ask what data migrations might be needed for current systems.
- Remember search reindexing.

### When Deploying...
- **Never** rush a deployment.
- Consider using a fork or parallel branch.
- Make a backup of settings and config for rollback if something goes wrong.

//todo: go back and add notes from work log and history slides.

## Questions to ask yourself instead of co-workers
- Are you on the correct branch? 
- Is your storage emulator running? 
- Is your database server running? 
