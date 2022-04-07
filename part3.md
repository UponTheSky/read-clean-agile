The former parts(1 and 2) are for explaining what is Agile and how to practice it in a broad sense. 
In this article, I would like to summarize the last parts of Uncle Bob's book. 
Although the last part is about half-size of the whole book, I thought some from it are not necessary to know the details and some are quite technical 
so I decided to omit them.  

# How do we practice Agile during a single cycle?

## Continuous Integration(build)
- Why do we need it? 
  - Since we commit in small size and check those commits constantly, we have to make tests that take care of even small things(TDD)

- How often do we have to build?
  - No golden rules, but you have to make your commits small

## TDD
- Why do we do TDD?
  - It encourages you to take a small step so that debugging gets much easier
  - Any small tasks get through tests: guarantees high-quality products
  - Being good at debugging is not something to be encouraged
  - Writing tests afterward wouldn't produce good tests(you may have to change your code, so you wouldn't dare to change the code)

- Test first means:
  - You'll design code that must pass the tests
  - It is good to make independent functions

- A test itself is a design, a documentation

- The most important merit of TDD is, that you would not be afraid of change in your code: you just need to make it pass the tests

## Refactoring
- Refactoring is a practice of enhancing the structure of code without changing its behavior
  - How can you be sure that the behavior wouldn't change?: that's why refactoring always goes with TDD

- Examples
  - Changing the name of a variable, a function, etc.
  - Splitting a complex function, a class, etc.
  - and many others...

- Refactoring is not something that you do in a certain period of time; rather, it is a part of writing your code

## Simple Design
- Kent Beck's principles of SD
  - Pass every test
  - Represent your purpose
  - DRY
  - Reduce the components

- Why do we need SD?
  - To reduce burdens on developers: Complex system means more time and effort are required to change the code and understand it
 
## Pair Programming
- I skip this part(I rather prefer reviewing)

## SW Tools for Agile
- One or more programming languages
- IDE 
- Data forms(JSON, XML, etc.) and Markup languages(for documentation, such as HTML)
- Tools for communication with OS: shell, bash, etc.
- VCS like Git
- CI/CD like Jenkins, TeamCity
- Deploy, Operating Tools: Docker, Kubernetes, Ansible, etc.
- Communication Tools: Slack
- For Testing: unit test, integration test tools like Selenium

### Remarks
- Tools are just tools: they are to be changed, and new competitors come out every year
- Don't work according to tools; rather, you set up your way of work first, then search for appropriate tools 

# Values of Agile
(By Kent Beck)The four values of Agile
1. Be brave for the quality 
2. Communicate with every relevant member
3. Frequent and fast feedbacks
4. Simplicity with respect to how you work

There are tons of things to say more about this book, but I find those summaries would be core messages from Uncle Bob, 
and I would certainly have them in my mind while I am working as a SW engineer. 
