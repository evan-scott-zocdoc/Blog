# Difference between Travis CI and Circle CI

### Continuous Integration
We have recently used both Travis CI and Circle CI to process our tests on two different projects and one - to our understanding - was our favorite.

Today and since its creation Travis CI has had considerable [more interest](http://www.google.com/trends/explore#q=Codeship,Travis+CI,CircleCI) than Circle CI. I have been wondering why. Is it that the Continuous Integration is simply more common in the industry, therefore it attracts more users? 
It may be part of the answer. The other part though, is that Travis has a longer history and therefore offers many more features than other Continuous Integration tools do. 
![]()
For one thing, we started using Travis in our first group project at Hack Reactor because it was the more visible tool we found.
After a discussion with Scott Moss, Hack Reactor's Lead Engineer, we decided to give Circle a try following strong arguments in favor of its simplicity of use. We were indeed blown away.

### Setup
Both setups are fairly straight forward. They require the following steps:
1. Sign up on their website
2. Set up a repository, or select the one you want to test. Then [create a YAML file](http://tech.pro/tutorial/1749/get-your-ci-on-with-travis-ci).
3. 

The installation with Circle CI took no more than five minutes while that with Travis took longer as we encountered issues. For one thing, we were amazed by Circle's [website](https://circleci.com/). It's so intuitive that the integration with our repository's test file was quasi-instantaneous. 

![](https://raw.githubusercontent.com/kxprim/Blog/master/travisVsCircle/circleWebsite.png)

### Use

The main difference of use was how the testers integrated with our workflows. Travis unfortunately doesn't offer integration with Slack, the centerpiece of our teamwork communication.

Therefore, we greatly benefitted from being notified everytime a test went through. The process of reviewing Git pull requests was optimized as we didn't need to check frequently if a test passed to then merge in the request.

 ![](https://raw.githubusercontent.com/kxprim/Blog/master/travisVsCircle/circleSlackIntegration.png)

Other than that, Travis CI offers its users tutorial for all sorts of programming languages. It's one of the benefits of using a more established software.	
 
### Conclusion
 
Especially if you are a beginner in the testing world I would recommend by far to start with Circle CI. Travis, due to its older age may have additional layers of complexity making it harder for the uninitialized to integrate at first.
