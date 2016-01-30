# Business Applications of Lessons Learned from Drupal Core Mentoring
#### DrupalCamp NJ 2016



## [bit.ly/mentoring-lessons](http://bit.ly/mentoring-lessons)

Note:
- Slides and speaker notes available online



## Cathy Theys

<a href="https://www.drupal.org/u/yesct"><i class="fa fa-drupal"></i> YesCT</a>

<a href="https://twitter.com/yesct"><i class="fa fa-twitter"></i> YesCT</a>

Note:
- About presenter



## Alina Mackenzie

<a href="https://www.drupal.org/u/alimac"><i class="fa fa-drupal"></i> alimac</a>

<a href="https://twitter.com/czaroxiejka"><i class="fa fa-twitter"></i> czaroxiejka</a>

Note:
- About presenter



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Starting small

Note:
- alina: We are talking about a lot of different concepts that evolved and were put to practice over time - rather than applying everything at once -- pick one thing and go with it / try it at your organization



### Small intitiative

Note:
- cathy: core mentoring started
 -- in IRC updating "new" issue summaries, and initially just triaging, reproducing to verify issues, now we have task documents for many types of contributor tasks, not just summary updates
 -- mentor sprints started with putting people all in one room at drupalcon denver, processes improved and grew overtime as we gained experience



### Organizational buy-in

Note:
- alina
- bringing change to a small group is easier than taking on large groups
- proposing an org-wide chatroom was easier once small group (7 people) had experience with it and we had evidence that it worked
- initial team become early adopters of techniques and share them with other groups
- organizational/institutional buy-in is important for growth
- to sustain growth, certain operational costs (time/money/policy) will have to be absorbed at a higher level
- example: Drupal Core Mentoring and DA
  - individual drives implementing ideas
  - DA takes over after pattern established and proven
  - frees up individuals to continue to evolve and improve process



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Talking in public

Note:
- cathy: talk in a public chatroom, even when you are in the same place in person
 -- move private conversations to public channels, make new public sub-topic channels to help manage the increase in chatter
 -- helps to avoid people repeating themselves
 -- do thanks in those public channels also, points, karma or kudos are nice



### Knowledge retrieval and transfer

Note:
- cathy: when people talk in public, knowledge transfer and retrieval is a public, accessible process
 -- when people share knowledge in a public chat, even those who are not directly in the conversation can benefit -- include publicly avialable storage of bits of information (factoids or bot responses of bits of commonly used information, commonly needed links or long links)
 -- safer, people can risk "answering" questions, cause if they are wrong, there are observers who can chime in with more information



### Story time

Note:
- background: team of 5-7 within a larger group of about 20. IT department of about 100?
- catalyst: adding a new team member, after a long time. at the same time, had 1-2 student workers
- need to disburse information in multiple directions, and have it checked/confirmed
- challenges: getting people to talk
- having a bot helps - store/retrieve information, get metadata about tickets
- comm platform doesn't matter, try using what you have (if it has group chat support)



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Asking questions

Note:
- alina
- exposing ignorance is difficult
- instincts tell us to feign expert knowledge, or at best stay silent
- asking questions is the best way to expose and address gaps in knowledge



### Increase engagement

Note:
- decreases fear, asking questions can be addictive
- learned more, and became more engaged
- shows other people that it's OK to ask, learn and grow



### Safe environment

Note:
- Environment must allow exposing lack of knowledge about something in a safe, productive way
- response cannot be surprise "what? you don't know x / how to use x?"



### Techniques

Note:
- have people say "thanks for asking that." "I've been wondering that also." as a way of supporting a cultural change where asking is ok and encouraged.
- have experienced people view the asking of a question as a signal that something needs changing: a doc needs to be more easily found, needs extra information



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Breaking down problems

Note:
- In Drupal Core Mentoring we come up against very large or extensive problems, and break it into tasks which on their own may seem trivial



### Breakdown

Note:
- for every such daunting problem (technological or not) the start can be "create an issue/ticket" - make a record. it plants a small flag where we are, so that we can start exploring even the most complex architectural solutions, identifying tasks, blockers
- taking a screenshot, correcting a typo in issue summary or clarifying words.
- Together these tasks become an integral part of the work toward a solution
- even for complicated issues, there are tasks that can be done by novices



### Patterns

Note:
- cathy
- experienced person ask new person for do first steps without asking to do large issue. once the first step is done, then give feedback to improve it or refine it. after that, give next step.
- when checking on status, don't ask: did you do that thing yet?, ask a more open-ended question like: what are you working on? this gives the other person opportunity to respond more accurately with more information "I am still reading through the comments on the issue"
- check for understanding assumptions when others write things down (rewrite what they were told to do)



### Benefits

Note:
- cathy
- with the overall issue split into smaller tasks
 -- eases fear (of starting)
 -- people can see they are making progress. this way, confidence builds as get to more challenging parts of a larger task. can also see things are "done" along the way. I did this little part. I can do this next little part. 
 -- in between the small pieces allows, mentor checks in about the smaller tasks
  --- give possibility for feedback before too much time going down the wrong path.
  --- Alina: I am often reluctant to ask for help: don't want to let my mentor down, go down the research rabbit hole instead of asking directly (relates to the Asking questions section)



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Feedback

Note:
- alina



### People are experts in their domains

Note:
- this is our starting point
- people who come to sprints (or a person new to a team) have experience in variety of domains
- including being an expert at being a beginner




### Three parts to feedback
- Thank you <!-- .element: class="fragment" -->
- Review <!-- .element: class="fragment" -->
- Next steps <!-- .element: class="fragment" -->

Note:
1. thank the person for their contribution (something specific you want them to repeat)
2. review and talk about what they did -- ask them to tell you what they did
  - people are more receptive to feedback given by machines (meaning, test suites), so have a test suite pointing out code formatting issues (trailing space) rather than a human
3. give specific suggestions for next steps, link to examples of similar work




<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Working together

Note:
- alina
- An issue is not solved by just one person from beginning to end (it cannot be, you can't review your own patches changes, in other words, you can't accept your own merge/pull request)
- There are multiple people come and do parts of the overall work



## Do not work primarily alone

Note:
- frequent check-in with others (ties back to Breaking down problems): people break off to do solo work, but check with one another throughout the day
- pairing - two people working together, switching control at intervals so that each person spends time typing



## Always be mentoring

Note:
- cathy



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## Moving on

Note:
- cathy



### Transition into and out of roles

Note:
- cathy



### Burnout

Note:
- alina



### Planned obsolescence

Note:
- alina



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
- talk in public <!-- .element: class="fragment" -->
- read a book <!-- .element: class="fragment" -->



## [Apprenticeship Patterns](http://chimera.labs.oreilly.com/books/1234000001813/index.html)</span>
David H. Hoover & Adewale Oshineye

Note:
-



<!-- .slide: data-background="custom/images/" data-background-size="" data-state="show-header" data-header="" -->
## [bit.ly/mentoring-lessons](http://bit.ly/mentoring-lessons)

Note:
-
