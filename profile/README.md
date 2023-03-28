# MGT858 - Database Systems, Spring 2023

Hello 👋👋! This is the "about" page for [MGT858 "Database
Systems"](https://858.mba) at the Yale School of Management in Spring 2023.
This is the first time I'm teaching this course and I'm super jazzed about it
🤩🥳. This is a living document — you can track changes by looking the git
commits. 

Jump to [Covid info](#covid).

## Overview

| Key                     | Value                                                                     |
| ----------------------- | ------------------------------------------------------------------------- |
| 🎓&nbsp;Course number           | MGT858                                                                    |
| 📚&nbsp;Units                  | 2 units in Yale College and equivalent elsewhere                          |
| 👥&nbsp;Enrollment             | Open to any student at Yale                             |
| 🕓&nbsp;Meeting Time | Tues. & Thurs. 13:00-14:20 EST, March 28 - May 11, 2023                 |
| 🏫&nbsp;Meeting Location | Room 2210 in [Evans Hall](https://map.yale.edu/place/building/EVANS?) |
| 💻&nbsp;Zoom link       | No zoom  🙁                                    |
| 📅&nbsp;Calendar | [Yale SOM Academic Calendar](https://som.yale.edu/programs/mba/integrated-curriculum/the-academic-calendar) |
| 🌐&nbsp;Website         | http://858.mba (down sometimes until class begins; requires Yale VPN)                  |


MGT858 introduces enrolled students to the database systems used in modern
technology companies.  You will emerge from this course an SQL ninja,
well-prepared for tech sector roles including data scientist, product manager,
and technical program manager.  The first half of the course covers relational
databases (those that use SQL, generally) and the latter half covers other
kinds of systems including key-value stores, document databases (noSQL),
distributed databases, graph databases, blockchain databases.  We will discuss
the business case for each of these database such that you ought to emerge from
the course able to think of a software product or service and describe what
kind of database systems ought to be used to build that product.  You will not
learn how to build such systems, though you will learn a little bit about their
internals. You will definitely learn how these systems can be used to answer to
the kinds of analytics questions you will encounter as a manager.  The
coursework includes *twice-weekly* homework assignments and a final
examination, all of which require writing code and must be submitted using the
git version control system.  (Experience with git is not required; however,
some experience programming is necessary. The particular language does not
matter.) Students can expect to spend perhaps six hours per week on homework.

## Admission to the class

You can be admitted to the class by bidding in the Yale SOM bidding system.
If you are ineligible for that or you didn't get your bid, you can test 
into the class. I will save five to ten slots for such students. I'll administer
a test covering version control and SQL on Friday, March 31st. I'll announce
the time in class. You must attend class the first week and be among the
top scoring students to join if you didn't bid into the class.



## How to use this document/repo

Because our class info and policies are tracked using git, you can see if and
how they change over the course of the semester. Further, you have the ability
to make changes yourself---please send me a pull request. Similarly, if you
feel these documents are lacking, please open an
"[issue](https://github.com/yale-mgt-858-spring-2023/about)" on GitHub for this
repo and we'll address the issue. Finally, because our git repo is hosted on
GitHub, you can easily receive push notifications of changes to this repo.
(Woot!)

## Office hours

Your first stop for help should be the [classroom discussion](https://github.com/orgs/yale-mgt-858-spring-2023/discussions)
on GitHub. Please only email if you need private help. 

The office hours for each of the teaching staff is shown
below. Though, if you are reading this before the start of
the semester, it is possible some staff are missing because
they did not yet determine their schedule. 

Feel free to send an email if these times do not work for you.

| Person          | Email | Hours            | Location/URL                                                                |
| --------------- | ----- | ----------- | ----------------------------------------------------------------------- |
| Kyle Jensen     | kyle.jensen@yale.edu | TBD | TDB |
| Adan Rivas   | adan.rivas@yale.edu | TBD | TDB |



## Development environment

You will need to write code a lot of code this semester, mostly domain-specific
query languages like [PostgreSQL-flavored SQL](https://www.postgresql.org/docs/).
Most of the homework assignments and the final exam will require using the [git
version control system](https://git-scm.com/) for submission. You'll sign up
for GitHub, join the [yale-mgt-858-spring-2023
organization](https://github.com/yale-mgt-858-spring-2023) on [GitHub](https://github.com/yale-mgt-858-spring-2023/.github/blob/main/profile/github.md) and
submit your assignments (in part) by pushing up code to GitHub. Usually I'll
give you some starter code like empty `.sql` files with examples queries.
When you complete your assignments, you'll make git commits and push those
commits up to GitHub so that I can download your answers and test them.
Obviously this requires knowing a little bit of git. I'll point you to some
git tutorials, but I'm not going to teach git in class. You are forewarned
😉. 

You can complete the homework assignments on any kind of computer: Windows,
Mac, Linux, whatever. You'll almost certainly need to install some software in
order to do so. Obviously you'll need git. You might also need _ clients_ for
different database systems. For example, you will almost certain need a
PostgreSQL client or a MongoDB client.  The `$XYZ` _client_ is a piece of
software that connects to the `$XYZ` _server_ in order to send the server
queries (or other commands) and interpret the responses. (Here, `$XYZ` is a
stand-in for PostgreSQL, Redis, MongoDB, Clickhouse, Elasticsearch, etc.) Now, it could be that you don't
want to set up the `$XYZ` client software on your computer, which would be totally reasonable: it
can be a pain in the rear-end. For this reason, you might want to use [GitHub Codespaces](https://docs.github.com/en/codespaces/overview)
for your assignments. You can find a lot of tutorials for doing that online. 


## Preparing for the course

I am receiving a few emails from students about how best to prepare for the
class. There's a few ways to think about doing so. One is to prepare narrowly
for the content you're going to encounter. For SQL, in my person opinion, the
best way to do so is going through the exercises at
[SQLBolt](https://sqlbolt.com/).  I think that website is fantastic and it's
part of the assigned reading in class. For the other database systems we'll
use, the answer is less clear.  You can read about
[ElasticSearch](https://github.com/elastic/elasticsearch) (the representative
full-text search database we might use);
[ClickHouse](https://github.com/ClickHouse/ClickHouse) or 
[DuckDB](https://duckdb.org/)
(the representative
columnar stores we might use); [Redis](https://github.com/redis/redis) (the
representative caching database we might use);
[MongoDB](https://github.com/mongodb/mongo) (the representative noSQL
database we'll likely use); and [Neo4j](https://github.com/neo4j/neo4j) (the
representative graph database we'll use).

A second way to prepare is to level-up your computer skills in general,
particularly your *nix skills. A good resource for doing so is [MIT's missing
semester course](https://missing.csail.mit.edu/).

Finally, you might think about getting your personal computer set up for
writing code. That usually starts with choosing a package manager
([homebrew](https://brew.sh/) on Mac OS and
[Chocolatey](https://chocolatey.org/) on Windows) and choosing a [good code
editor](https://github.com/collections/text-editors). I use
[VSCode](https://code.visualstudio.com/) and [NeoVim](https://neovim.io/).

Also 😜, you'll want to be familiar with [git](https://git-scm.com/). You can
find [many tutorials
online](https://medium.com/@javinpaul/top-10-free-courses-to-learn-git-and-github-best-of-lot-967aa314ea).
Your use of git this semester will be super simple because you won't generally
have collaborators. If you like, you can use a [git GUI](https://git-scm.com/downloads/guis).
I use GitHub Desktop often, mostly for line-by-line staging of changes.


## Textbook

There is no textbook for the course. Readings will be posted on the
[class website](https://858.mba).

## Diversity, equity, inclusion and their opposites

This class will be an inclusive environment. If you see behavior
that you feel is discriminatory, _particularly_ from the professor
or teaching staff, we encourage you to avail yourself of one or
more of the following resources.

- [Preventing and Responding to Sexual Misconduct at Yale Booklet](https://smr.yale.edu/sites/default/files/files/Guide-Preventing-and-Responding-to-Sexual-Misconduct.pdf)
- [Yale
  Sexual Harassment and Assault Response & Education (SHARE)](https://sharecenter.yale.edu/)
- Diane Temple in SOM Human Resources and Sheri Scully in the SOM AASL.
- [Yale Title IX Coordinators](https://provost.yale.edu/title-ix/coordinators) (SOM’s Title IX Coordinator is Rebecca Udler)
- [Yale's Live Safe App](https://your.yale.edu/community/public-safety/campus-safety-services/livesafe-app)
- [Office for Equal Opportunity Programs](https://equalopportunity.yale.edu/)

## Homework assignments

We will usually have two homework assignments per week and a pre-class quiz
before every class. That's
a *lot* of work!  All of the homework assignments will be submitted to
GitHub using git. 

## Use of AI assistants, human assistants, and the honor code

You should totally be using AI assistants such at GitHub Copilot
(best for writing code) or ChatGPT (good for answer pre-class quiz
questions). I ask that you not copy from other humans in "real-time".
You are welcome to use the advice of other humans through media
such as StackOverflow or our [class
discussion/qa](https://github.com/orgs/yale-mgt-858-spring-2023/discussions)
and also to work on your homework with your colleagues. Given such
parameters, what do I think would constitute a violation of the
honor code? I can think of a few things: 1) blatant copying,
particularly in serial; 2) wide spread dissemination  of answers
to quizzes or homework assignments; 3) copying from a human in
real-time; 4) use of unauthorized resources during the final exam;
5) efforts to thwart faithful grading, such as fibbing about time
of submission.  What's the bottom line? We're all adults. I want
you to learn, I want you to have fun, and I want to faithfully
report a grade that reflects your "real world" subject matter
competence at the end of the term. Don't do things that mess that
up.

## Quizzes

Most classes are preceded by a quiz that you take
through the class website. The quizzes are short, timed, multiple choice,
mandatory, and ultimately a crude and imperfect assessment of
the degree to which you understand the pre-class reading material.
The following are my reasons for giving pre-class quizzes:

1. It makes you think about the upcoming class!
2. Empirical evidence shows that the [testing effect](https://en.wikipedia.org/wiki/Testing_effect)
   increases your understanding and retention of material.
3. They give you a low-stakes, super-small reward for coming to class prepared.
4. They ensure that your classmates are better prepared for class and therefore more fun to speak with.
5. They are short, you can google for stuff during the quiz, _and_ you
   can drop your lowest two scores, so they are not stressful.

You take the quizzes via the class website. Click on "meetings" then click on
the meeting for a particular class. (You can also take the quizzes via the
class API. If you're a masochist, contact me! 🤪) A button that says "Begin Quiz"
will appear if you can take the quiz.  Once you begin a quiz, you can change
your answers until either 15 minutes after you began the quiz, or the closing
time of the quiz, which is usually the beginning of class. So, if you start a
quiz five minutes prior to class, you will only have five minutes to submit the
answers to the quiz questions! The quizzes are graded only after the quiz
closes. Kyle will sometimes go over the content of the quizzes at the beginning
of class.

You can take the quiz if all of the following are true:

- The quiz is not labeled as "draft". Draft means the teaching
  staff are still working on the quiz questions.
- The current time is after the quiz is "open". Quizzes usually
  open five days before the meeting/lecture to which the quiz
  corresponds.
- The current time is not after the quiz is "closed". Quizzes
  usually close when the meeting/lecture to which the quiz
  corresponds begins.
- You did not previously take the quiz or you already started
  the quiz, but your time to take the quiz is not expired.
  All quizzes this semester will last 20 minutes.

Once you click "Begin Quiz", you will see a list of multiple
choice questions displayed in an HTML form. For each question,
you should select the options you desire and then click
"Save Answers" at the bottom of the page. Unless there is an
error, the options that you selected will be labeled as "saved",
so that you have visual confirmation.

A few notes about the quizzes...

* The quiz questions are not uniformly drawn from material in
  the pre-class reading. Some pre-class reading will be over-represented
  and some under-represented either, usually because of heterogeneous
  importance of the pre-class reading material.
* We want the quiz questions to test your conceptual understanding.
  We do not want to ask "gotcha" questions or simple recall questions.
  However, we will fall short in those aspirations often.
* Some quiz questions will have obvious answers. We do this in part
  to remind you of important concepts.
* If you feel like a quiz questions is unfair or that the answer
  is wrong, please tell Kyle. It is easy for Kyle to "fix" a bad
  question.
* Questions that have multiple correct answers are indicated as
  such in the class website.
* There is a timer at the bottom of the page in the quiz UI on 
  the class website. It shows the *approximate* time you have left
  to finish your quiz. Please monitor your time.
* It is 100% fine to google for the answers to quiz questions or to
  look in the reading material. You may not rely on another human
  being for real-time support on the quiz and you may not share
  information about the quiz with other students. You can use
  AI assistants.

## Grading

Grading will follow the [official Yale SOM grading
policy](https://portal.som.yale.edu/page/grade-policy-mba-mam-mms).  That is
_essentially_ a forced curve: a certain number of students get each grade: HH,
H, etc. In my opinion, it's a quite generous curve (though [the ethics of
grading on a curve are
dubious](https://digitalcommons.law.byu.edu/cgi/viewcontent.cgi?httpsredir=1&article=1153&context=elj).
I will compute the grades for non-SOM students by overlaying their school's
grading scale on top of the SOM curve. There's not a 1-to-1 correspondence.
Your letter grade will be based on your sum grade and your sum grade will be
determined _roughly_ as follows (I reserve the right to make changes. The most
common change I make is dropping assignments.)


| Component       | Percentage            | 
| --------------- | ---------------- |
| Homework     | 30% | 
| Quizzes   | 30% | 
| Final exam   | 30% | 
| Participation   | 10% | 

The ethics of counting participation in the grade are also a bit dubious 🙁.
But, I'm including it for consequentialist reasons: your participation makes
the class more fun for all of us and most importantly for me 🤣.

## Class meetings

This is a half term course. You can see the schedule here: [https://858.mba](https://858.mba).

