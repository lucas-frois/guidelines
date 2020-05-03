# Guidelines
Guidelines to general development. Made by [@frvs](https://frvs.now.sh/).

###### Note: for this guide I've use [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Check for more info about Markdown.

### Versioning 
Use Semantic Versioning or [SemVer](https://semver.org/), the commonest versioning system.   
You probably have seem it before: something like `1.3.2` version. [Telegram changelog](https://desktop.telegram.org/changelog) is a good example.  
Also, check about how to keep a good [CHANGELOG](https://keepachangelog.com/en/1.1.0/).

### Git flow
On a personal project, isn't common to make a good using of **branching**.  
If you're working for a company or pretends, take a look at [Git Flow](https://danielkummer.github.io/git-flow-cheatsheet/index.html) to help you. 

### Communication
Soft skills makes a huge difference.  
Learn to communicate properly, to ask for help and to listen more.  
[Asynchronous communication](https://doist.com/blog/asynchronous-communication/) is a good way to start it.

### Documentation 
Make your code maintenable.  
Check [for the Github Guide](https://guides.github.com/features/wikis/) and [a handbook](https://github.com/jamiebuilds/documentation-handbook) to learn more about.

### Contributing
Make your projects open to contributions is a good practice.  
Look for some examples to create your own guidelines: [a good contributing.md template](https://gist.github.com/PurpleBooth/b24679402957c63ec426) and [Github guide](https://help.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors).
Make sure to read the guidelines from the Open Source Projects (OSS) you want to contribute.

### Testing
Personal opinion: **[unit tests](http://softwaretestingfundamentals.com/unit-testing/) are indispensable and all developers must implement it**.  
You can look for *test-driven development* or other kinds or *n-driven developemnt* (BDD, DDD) if you want.  
Other common test types are **stress tests** and **integration tests**. Check that if you're developing something important.

### HTTP protocols
Most of production software in 2020 are client-server applications.  
Based on that, you should know something about ways to comunicate on the both sides of your application.  
Years ago, you could use *Simple Object Access Protocol* (SOAP) to do this. However, Representational State Transfer (REST) is the present.  
Learn about [RESTful APIs](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9). 

### Stacktraces
Being able to know what's going wrong in your code is **essential**.  
In my junior developer experience, isn't common to do code without any error.  
Learn to read stacktrackes. Google it from your favorite language: `e.g. how to read [dotnet/your language] stacktrace`. This must be useful.

### Atomic commits
Atomicity is a common topic on technology development.  
You could heard about it in [databases](https://vladmihalcea.com/a-beginners-guide-to-acid-and-database-transactions/), [front-end patterns](https://bradfrost.com/blog/post/atomic-web-design/) and so on.  
Here, we want to talk about [**atomic commits**](https://www.freshconsulting.com/atomic-commits/) best practices. 

### Deployment
![devopsjoke](https://github.com/frvs/guidelines/blob/master/devopsjoke.jpeg "DevOps  joke")
Since **DevOps** turned into a technology keyword, the [**full cycle developer**](https://netflixtechblog.com/full-cycle-developers-at-netflix-a08c31f83249) became more and more valuable.  
###### `Check the Netflix's blog post about full cycle development above.`
It'll be nice if you're able to code **and deploy** your application. There are two main options:

### Zero config deploy
You're a newbie on programming and don't want to care too much about it, start here.  
The Vercel product, [Now](https://vercel.com/docs), is a place to deploy your apps just connecting to Github. It's awesome.  
For back-end focused alternatives, [Heroku](https://devcenter.heroku.com/start) is awesome too. Take a look.

### Dockerfile and pipelines 

Otherwise, I'll probably face a Dockerfile plus .yml file (stands to pipeline file) to deploy your application.    
Look for some [Dockerfile guide](https://rollout.io/blog/a-beginners-guide-to-the-dockerfile/) and google a tutorial for your favorite deploy player pipeline configuration.
```
e.g. google: [circle ci/other player] pipeline configuration
```
### Learning 
There's a confusing difference between *Documentation/reference guide*, *How-to guides* and *Learn-by-example guides*.  
Take a look at [Divio](https://documentation.divio.com/). It covers the differences and how to read each tutorial.

### Conclusion
hmm am i good at it? no
![conclusion](https://github.com/frvs/guidelines/blob/master/doesntmatter.png "conclusion")

###### Useful links, blogs and etc
###### * [Roadmap.sh](https://roadmap.sh/)
###### * [My blog](https://frvs.now.sh/blog)
