# Learning-Log
#### Some level of growth documentation. See also personal rules developed from these experiences and more. 

## Angular
---
- When working with a component from a package, don't treat the package like a black box. Find the code wherever it's hosted and figure out how it works. IOW `F12` everything if documentation isn't available. (11/11/21)
  
## ASP.NET Core
---
- Lucene is a super powerful text search engine. The concept of inverted mappings is brilliant. (1/7/22)
- LukeMapper is a great micro-ORM. Still need to dig into it more. (1/7/22)
  
### Migrations
- When performing a data migration that is specific to one area of the system, it is not necessary to update pre-release package versions for unaffiliated (yet dependent) microservices. This, of course, is not the case if the migration is changing models. (5/2/22)
### NuGet
- Make sure you have the correct package sources, and that they are appropriately enabled. (3/16/22)
- To clear local caches, make sure nothing is using NuGet (kill all running dotnet projects and maybe close VS). (3/16/22)
  - `dotnet nuget locals all -c`

## Azure
---
### Azure Devops
- How to add gh workflows, deploying to azure, deploying a django project. (12/6/21)

### Azure App Service
- Filename case matters! It might run locally, but it will break on app service if it's not a perfect case match. (12/14/21)

## Debugging
---
- If a parent component is not recieving the expected information from the child, dig into the way that the child is working. Odds are an event isn't being fired. (11/2/21)
- If you're not sure why properties on an object are the way that they are, check the DB to see if other instances/versions of that object have matching properties. If not, you might be dealing with bad data. (11/12/21)
- When you're stuck, write out a comment detailing what you know and what questions remain. Doing so will help you think through the problem and figure out what's going on. (11/12/21)
- Develop a first instinct to look at the output, break into the code, see what is happening where. 
  - What is the flow of data? 
  - What is the context? 
  - What extrinsic factors are in my control which might be affecting the state of the application? Inputs? Integrations? Dependencies? (1/25/22)

## Process 
---
- There are multiple solutions to every problem, so think through three as you consider all angles. (12/6/21)
- You can try to directly translate small tutorials onto your bigger proejct immediately, but it will probably be a waste of time. Either before or after that, complete as small of a tutorial as possible. Learn the concepts, get the win, and then apply what you've learned to your bigger project.
- Never rush a deployment. Make a parallel deployment, create a backup of settings and config for rollback if something goes wrong. Take the time to configure multiple environments so you can run it locally and verify. (12/7/21)
- Make a list of questions to ask when you're blocked. (Are you on the right branch? Latest? Storage emulator running? etc.) (12/7/21)
- Even if you're short on time, have goals for the day. Check on your progress at least every hour, and make sure you're working towards your goals. (1/6/22)
- If you feel lost on a topic, type out a message to your team in a note. Odds are you will think of a new question to google, and often enough, it will lead you to answers. (1/7/21)
- Get wins quickly. (1/25/22)
  - Take a moment to connect how the win will help you realize your vision of company and personal growth. 

- Pull the latest changes on all feature branches daily! 
  - You should also do this on the dev/master branches for other services, but it's especially important to do it on every feature branch. (4/7/22)

### Feeling Stuck
- When feeling stuck, draw it out. 
  - If you spend more than 30 minutes planning on your own, call someone in or just get started and re-evaluate in 30. 
  - If you don't know everything, but you do know some things, jump in on those things and ship something daily. (1/19/22)
- If something just doeesn't make sense, pull the latest on everything! Assume that others are fixing things. (4/7/22)

### Handling Distractions

## People
---
- Always celebrate the victories, successes, and contributions of others.
- Be quick to compliment ingenuity, effort, and thoughtfulness.

### Disagreements
- If you think you have a better way, ask something like "Is there a disadvantage to...?"
- If you think your superior is wrong, pose questions like "I just want to make sure I understand. If we do this, will...?"
  - Then, be willing to go to lengths to test their assumptions and try to prove them right. Find the faults in your own ideas before theirs. Even if you would prefer your proposal, avoiding contention is a high priority.
  - If their proposal proves infeasible, present the evidence humbly, and with validation for the idea. (5/2/22)