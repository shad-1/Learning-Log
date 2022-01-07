# Learning-Log

## Angular
- When working with a component from a package, don't treat the package like a black box. Find the code wherever it's hosted and figure out how it works. IOW `F12` everything. (11/11/21)

## ASP.NET
- Lucene is a super powerful text search engine. The concept of inverted mappings is brilliant. (1/7/22)
- LukeMapper is a great micro-ORM. Still need to dig into it more. (1/7/22)

## Debugging
- If a parent component is not recieving the expected information from the child, dig into the way that the child is working. Odds are an event isn't being fired. (11/2/21)
- If you're not sure why properties on an object are the way that they are, check the DB to see if other instances/versions of that object have matching properties. If not, you might be dealing with bad data. (11/12/21)
- When you're stuck, write out a comment detailing what you know and what questions remain. Doing so will help you think through the problem and figure out what's going on. (11/12/21)

## Azure Devops
- How to add gh workflows, deploying to azure, deploying a django project. (12/6/21)

## Azure App Service
- Filename case matters! It might run locally, but it will break on app service if it's not a perfect case match. (12/14/21)

## Process 
- There are multiple solutions to every problem, so think through three as you consider all angles. (12/6/21)
- You can try to directly translate small tutorials onto your bigger proejct immediately, but it will probably be a waste of time. Either before or after that, complete as small of a tutorial as possible. Learn the concepts, get the win, and then apply what you've learned to your bigger project.
- Never rush a deployment. Make a parallel deployment, create a backup of settings and config for rollback if something goes wrong. Take the time to configure multiple environments so you can run it locally and verify. (12/7/21)
- Make a list of questions to ask when you're blocked. (Are you on the right branch? Latest? Storage emulator running? etc.) (12/7/21)
- Even if you're short on time, have goals for the day. Check on your progress at least every hour, and make sure you're working towards your goals. (1/6/22)
- If you feel lost on a topic, type out a message to your team in a note. Odds are you will think of a new question to google, and often enough, it will lead you to answers. (1/7/21)
