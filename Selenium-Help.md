# Getting Help with Failing Tests

## Before We Begin

Is this a [frequently asked question](FrequentlyAskedQuestions.md)? If it's not, be aware that you won't get help in the comments section of this page. So what should you do?

## It's Not a FAQ

If you're experiencing problems running a selenium test, and think that it may be selenium's fault, please email the "webdriver" or "selenium-users" group with the following information:

  * Symptoms
    * What the problem?
    * Does it happen every time you run the test?  If not, how frequently?
    * Are others on your team experiencing the problem?
    * A link to a [gist](http://gist.github.com/) of any interesting stack traces
  * What you've tried so far
    * Are you able to reproduce the failure on other browsers?
    * Do you have other changes in your code that might be affecting this test?
  * Steps to reproduce
    * Which OS, browser and version of the browser are you using? This is vital.
    * Ideally, a minimal test case against a public site we can run. Here are some templates you can use to create a test case: [Ruby](https://gist.github.com/1024843)
    * How to run the test (if there's any special set up needed)
    * It is also very helpful if you can create a [reduced test case](http://www.webkit.org/quality/reduction.html)
  * Anything else we should know?
    * Such as which OS, browser and version of the browser are you using. It's such an important bit of information that we thought we'd mention it again :)
# Why We Need This Information

We want to help you fix the problem. The best way to do this is if we can replicate the issue on our local machines. You're the person who knows best about how to build and test your application.

Patches are extremely welcome if you solve a Selenium bug!