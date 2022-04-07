This is a book by "Uncle Bob". To be honest, this is the first book I ever read from those myriads of good books written by him. 
But why not "Clean Code" or "Clean Architecture" first?

Recently I joined a startup company as a PM(but it is a rather supportive position than you might think of a PM at an IT company). 
Hence I have to figure out what is a good working process for product delivery. 
In that sense, I really enjoyed this book since it tells me almost everything I need to know or think over!

The followings are some kind of a summary(maybe takeaways) of this book.
I don't ever mean to copy the message, but rather, I encourage you guys to read this amazing story from Uncle Bob.

# Intro to Agile

## How did Agile come out to the world?

- Both waterfall and agile were not new at all; they are 
very intuitive methodologies for a work process.
- Then why agile? Waterfall was popular before agile came out, and it shows many problems. 
- There were XP, Scrum, and others before the manifesto.
- Then we have [the Agile Manifesto](https://agilemanifesto.org/)

## What is Agile?

- Iron Cross: Good, Fast, Cheap, Done
- Agile is a system for helping PM practically
- Agile provides data: speed chart, and burn-down chart 
- You need to know how fast the team is moving, and how much works have been left to be done.

## Why do we need Agile? Why does Waterfall fail?

- You have your deadline
- Clients don't know what they want: you would encounter changes in requirements very often

## How exactly an Agile process works? What is an exemplary approach?

1. First, you are given the due date of a project

2. Second, break down the whole timeline into units, where each unit is a week or two(= cycle, sprint)

3. Now, in cycle 0, you set up an overall plan: analysis, design, environment setup. But not that thoroughly as Waterfall. Rather, we call each small functionality to be added as a "story". So at this phase, you set up a bunch of stories that constitute the whole project. Of course, it is imperfect. Rather, it must be simple. 

4. From cycle 1, you measure actual progress by how each story has been completed. By around cycle 5, we may estimate how many stories the team could finish up since we have got data now.

5. Remember that we do analysis, design, and implementation in each cycle. It is not a collection of small Waterfall processes.

6. Now, based on the data collected, the team can estimate speed, quality, and cost for the whole project. It is on the team's hands to discuss and compromise with the business side.

Uncle Bob recommends the XP methodology in this book.

# Why Agile?

Ultimately, it is to deliver high-quality products to clients

## Several Principles to Follow:

- Every cycle must end with a deployable state "technically"
  - The code must be clean, and every test is passed
  - So documentation and reliability issues are guaranteed

- Sustainable productivity
  - Clean architecture, design, and code ensure it
  - Same functionality must take almost the same story to be implemented
  - No re-design from scratch

- flexible to changes
  - This is what Agile is really for, or SW itself is really for
  - Do not fear changes! 
  - Simple design, TDD, Refactoring

- Make QA do as little works as possible
  - Automated tests, Acceptance tests, CI

- Communication between teams, and the biz-side people

- Exact estimation: as a probability distribution

- Mentoring, relentless learning


## Bill of Rights

- Clients have rights to:
  - know the whole plan; what, when, at how much cost
  - have as much value as possible for each cycle
  - know how everything goes; how everything passes the tests
  - change the priority or functionality without much extra cost
  - be informed when the schedule & estimation has changed
  - cancel a project at any time

- Developers have rights to:
  - know the priority exactly outlined and the requirements at least within a cycle
  - produce high-quality results
  - ask for some help from others
  - make estimations and change them
  - say no!
