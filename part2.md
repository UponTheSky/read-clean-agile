More than my initial expectation, the book is concise and has a myriad of valuable messages. 
Thus I have decided to divide this study into three parts. But I won't summarize all of them - only gathering the messages I think important to remember.

# How to practice your business?

## Set up the plan

- Make your estimation fast, but as exact as possible
  - Trivariate estimation: show the best, average, and worst cases => not exact enough for a normal-sized project

- Story point(in the cycle 0)
  - So what is a (client)story?: functionality defined as simple as possible from the viewpoint of the client
  - Why simple? You could not be sure those details could all be well implemented in the future => inestimable, useless
  - Now estimate a story: make the **golden story** that is our standard so that you can estimate others based on that story

- Planning the first cycle
  - IPM(Iteration Planning Meeting): around 1/20 of a cycle
  - Everyone relevant should attend this IPM
  - At this phase, we select stories to be implemented, based on the business priority
  - The speed/point/estimation is not a promise

- Middle check
  - At least You'll have data now: how many story points you could finish within a cycle
  - a project does not finish when all the stories have been implemented; rather it finishes when there are no stories valuable to be implemented

- Some principles when writing stories
  - I: Independent(as much as possible)
  - N: Negotiable(so we don't put in that many details)
  - V: Valuable(in a business sense)
  - E: Estimable
  - S: Small(one or two developers should be able to implement within a cycle)
  - T: Testable

- Splitting, Merging, and Spike
  - Merging is easy, but splitting is something to be cared for, keeping the principle INVEST
  - A spike is a meta-story: a story for estimating a story
  
## How to manage the cycles?

- Rather than make progress in each of the stories, it is more important to finish the individual stories
- Story assignment is left to the developers
- QA & Acceptance test: at least before the former half of the cycle, ATs must be done
- QA writes tests before the next cycle begins
- QA & developers must be closely bound with each other

- A task(story) is completed when it passes the ATs
- We only record on the story point board those stories that are "completed"; no 90% or something

- Showing DemosL after a cycle, we show demos, with all tests are being passed

- As the project goes along, we record the speed graph and the burn-down chart
  - to prevent point inflation(coercing developers to work harder), we need to compare the current estimation result to the past golden standard.

## Small Release 
It is desirable to release in a short term. Today, we have the concept called 'CD'(continuous delivery)

## Acceptance Test

The business part specifies the requirements(specification), and they are basically "Tests".

- What Agile means by "AT", it can be automated
- But then who would write tests? Biz? Devs(QA)? => together
  - Biz analyst: only describes successful ways
  - dev: need to see whether the tests are reasonable in tech's sense
  - QA: try some edge cases, malicious cases as well

- So this way of working brings the responsibility of the QA teams to each of the cycles, and relieves some burden from them before the final test and release

- This all comes with CB(Continuous Build)

## The Whole Team
Product owner(client) - communication - developers

- good for communication
- everyone of interests gather together in a single place
