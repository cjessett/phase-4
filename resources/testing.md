# Testing

Tests come in many different shapes and sizes, and until this point we haven't made clear distinctions about what kinds of tests we want you to write.  While there are certainly other kinds of tests, there are three main categories of testing that you should be familiar with: unit tests, integration tests (i.e. ["subcutaneous" tests](http://martinfowler.com/bliki/SubcutaneousTest.html)) and behavior tests.

## Unit tests
Most of what you've seen so far falls under this category.  A unit test strives to test, in isolation, the smallest possible "unit" of code, usually a function or particular path through a function.  Mocking tools like [RSpec Mock](http://www.relishapp.com/rspec/rspec-mocks/v/3-5/docs) allow you to write tests without worrying about how that function interacts with the rest of your application.  Unit tests should almost never hit a database or a service, though they may verify that the correct API calls are being made.

## Integration Tests
Once you've got a solid base of unit tests you know with some amount of confidence that the individual pieces of code work as intended.  But do they work together the way you want them to?  That's the job of integration tests.  Integration tests often start at a service or API level, hitting a database of testing data and using services running in a dedicated testing/development environment.

## Behavior Tests
We now have a test base that's covering individual code units and integration at the API/service level.  That's great!  But what about the actual application that our users are going to be clicking around in?  Is the *behavior* of the application what we expect it to be?  Tools like [Selenium](http://docs.seleniumhq.org/) and [Capybara](https://github.com/jnicklas/capybara) allow us to write tests that launch a browser (headlessly) and actually click around our web app, testing its behavior.  Because these tools rely on CSS and HTML elements to do their work they're often much more brittle and expensive to maintain than unit or integration tests.  If we change or remove a class a test relied on, it will break, tying front end development and design to testing.  Because of the cost and fragility of behavior tests, they're generally only advised for the most critical paths in your application (i.e. the parts of you application that will prevent you from making money if they're broken, think credit card processing or new user registration).

Because of the relative costs to build, run and maintain the different types of tests, it's usually a good idea to have many unit tests, fewer integration tests, and just enough behavior tests to cover your critical paths.  This gives us the testing pyramid:

![Testing Pyramid](http://martinfowler.com/bliki/images/testPyramid/test-pyramid.png)

## Why so many tests?
Different kinds of tests catch different kinds of bugs.  No amount of unit tests can protect you from incorrectly integrating your classes.  Additionally, as you can see from the chart below, no individual type of testing has a particularly high rate of defect detection.  When you use them together, however, you can achieve much, much higher rates of defect detection.

![Defect detection rates](./defect-detection-rate-mcconnel.png)
