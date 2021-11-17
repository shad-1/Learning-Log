# Personal Rules
## A Programmer's Guide to avoid breaking everything, primarily from experience breaking things.

### When merging a feature...
- Always be positive you are merging __all__ involved branches. 
    - __**Do not** count on the workflow management tool to accurately report which branches are involved__.

### When reviewing code...
- If it is a **SQL migration**, check for hardcoded database references. Different environments will likely have different database names. Reference tables instead.

### When Planning a Story...
- Consider possible regressions.
- Ask what data migrations might be needed for current systems.
- Remember search reindexing.

//todo: go back and add notes from work log and history slides.