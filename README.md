# Learning-Log

## Angular
- When working with a component from a package, don't treat the package like a black box. Find the code wherever it's hosted and figure out how it works. IOW `F12` everything. (11/11/21)

## ASP.NET

## Debugging
- If a parent component is not recieving the expected information from the child, dig into the way that the child is working. Odds are an event isn't being fired. (11/2/21)
- If you're not sure why properties on an object are the way that they are, check the DB to see if other instances/versions of that object have matching properties. If not, you might be dealing with bad data. (11/12/21)
- When you're stuck, write out a comment detailing what you know and what questions remain. Doing so will help you think through the problem and figure out what's going on. (11/12/21)

## Azure Devops
- 



add gh workflows, deploying to azure, deploying a django project, django learnings and process rules


- process: 
- multiple solutions to every problem
- you can try to directly translate small tutorials onto your bigger proejct immediately, but it will probably be a waste of time. Either before or after that, complete as small of a tutorial as possible. Learn the concepts, get the win, and then apply them to your bigger project.
- Never rush a deployment. Make a parallel deployment, create a backup of settings and config to be able to roll back if something goes wrong. Take the time to configure multiple environments so you can run it locally and verify. 
...
- make a list of questions to ask when you're blocked. (are you on the right branch? Latest? storage emulator? etc.)
- Even if you're short on time, have goals for the day. Check on your progress at least every hour, and make sure you're working towards your goals. (1/6/22)

## Azure App Service
- Filename case matters! It might run locally, but it will break on app service if it's not a perfect case match. (12/14/21)