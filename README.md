# Guidelines
Guidelines to general development. Made by [@frvs](https://frvs.now.sh/).

### Versioning 
Use Semantic Versioning (aka [SemVer](https://semver.org/)). At the same time, check about [CHANGELOGs](https://keepachangelog.com/en/1.1.0/).

### Git flow 
Use [Git Flow](https://danielkummer.github.io/git-flow-cheatsheet/index.html) to help you in a development n deploy flow. 

### Communication
Learn about [asynchronous communication](https://doist.com/blog/asynchronous-communication/).

### Documentation 
Make your code maintenable. Check [here](https://guides.github.com/features/wikis/) and [here](https://github.com/jamiebuilds/documentation-handbook) to learn more about.

### Testing
Personal opinion: **[unit tests](http://softwaretestingfundamentals.com/unit-testing/) are indispensable and all developers must implement it**.  
You can look for *test-driven development* or other kinds or *n-driven developemnt* (BDD, DDD) if you want.
Other common test types are stress tests and integration tests. Check that out if you're developing something important.

### HTTP protocols
Most of production software in 2020 are client-server based. Starting there, you should know something about ways to comunicate on the both sides of your application.  
Years ago, you could use SOAP (*Simple Object Access Protocol*) to do this.  
However, REST is the present. Learn about [RESTful APIs](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9). 

### Stacktraces
Being able to know what's going wrong in your code is **essential**. In my junior-mid developer experience, isn't common to do code without any error.  
Learn to read stacktrackes. Google it from your favorite language: *how to read [dotnet/your language] stacktrace*. This must be useful.

### Atomic commits
Atomicity is a common topic on technology development. You could heard about it in [databases](https://vladmihalcea.com/a-beginners-guide-to-acid-and-database-transactions/), [front-end patterns](https://bradfrost.com/blog/post/atomic-web-design/) and so on.
Here, we want to talk about [**atomic commits**](https://www.freshconsulting.com/atomic-commits/) best practices. 

![devopsjoke](https://codelabs.nyc3.digitaloceanspaces.com/contents/January2020/opjYQ1DwMbi0enlqegDTl3tpSlhKSSSS.jpeg "DevOps  joke")

### Deployment
Since **DevOps** turned into a technology keyword 
