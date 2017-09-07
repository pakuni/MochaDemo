Learn Coveralls 
===============
[![Build Status](https://travis-ci.org/nelsonic/learn-coveralls.io.png?branch=master)](https://travis-ci.org/nelsonic/learn-coveralls.io) [![Coverage Status](https://coveralls.io/repos/nelsonic/learn-coveralls.io/badge.png?branch=master)](https://coveralls.io/r/nelsonic/learn-coveralls.io?branch=master) [![Code Climate](https://codeclimate.com/github/nelsonic/learn-coveralls.io.png)](https://codeclimate.com/github/nelsonic/learn-coveralls.io) [![Dependencies](https://david-dm.org/nelsonic/learn-coveralls.io.png?theme=shields.io)](https://david-dm.org/nelsonic/learn-coveralls.io)

Coveralls helps track code coverage in your Node.JS & Browser JS projects

![Rainbow Unicorns](http://i.imgur.com/HRG0EVa.png "Rainbow Unicorns")

***100% Code Coverage*** is no Myth.
Its not only *possible*, it needs to be the ***New Normal***.

## Intro

### What is Code Coverage?

Code coverage measures how much of your source code is tested. 
A program with high code coverage has been more thoroughly tested 
and has a *lower chance* of containing software *bugs* than a program
with low code coverage.

#### Read more:

- Wikipedia article: http://en.wikipedia.org/wiki/Code_coverage
- What is Code Coverage: http://stackoverflow.com/questions/1158518/what-is-code-coverage
- StackOverflow Discussion:  <br />
http://stackoverflow.com/questions/195008/what-is-code-coverage-and-how-do-you-measure-it

#### Note

In the absence of other *objective* measures of code quality, 
projects I have worked on in the past use code coverage as our benchmark. 


### Why is Code Coverage Important?

While having 100% code coverage *does* ***not guarantee*** that your code is
free from *any* bugs, it does ensure that every line is 
being "exercised" so there is *less likelihood* of ***unexpected behaviour***. 

This ***reduces uncertainty*** *and* ***increases confidence*** in the code 
written by everyone on your team.
So when a bug does *inevitably* get discovered, you know


### What is Coveralls

Coveralls is a code coverage checking service. <br />
It does one thing well: tracking code coverage. <br />
It's *free* for open source projects so get started *today*!

Features: https://coveralls.io/info/features

## Get Started

### Node.JS 

For Node.js the easiest way is to use: 

- **node-coverals** (by Gregg Caines): https://github.com/cainus/node-coveralls
- [**Mocha.js**](http://mochajs.org/)
- [**Istanbul**](https://github.com/gotwarlost/istanbul)

Other options are available. see: https://coveralls.io/docs/node

#### Some Code

Before we can check code coverage we need to write some code!
But since this is not the *focus* of this tutorial, I'm not going
to dwell on it too much. 

For a more detailed look at the code used here, see: 
https://github.com/nelsonic/learn-mocha

#### Visit Coveralls.io

Navigate to: https://coveralls.io where you will see a 
"Sign in with GitHub" button.

![Coveralls login w GitHub](http://i.imgur.com/jAXLW6o.png "Coveralls login")


#### Add Repo

Click the "Add Repo" link:

![Add Repo](http://i.imgur.com/Q9T54Bq.png "Add repo")


#### Find your Repo and Flip the Switch 

![Flip Switch](http://i.imgur.com/rNFNsJK.png "Flip Switch")


#### Create .coveralls.yml file and Add Token

![repo_token](http://i.imgur.com/D3CE8Mt.png "repo_token")

Get your repo_token from coveralls and create a **.coveralls.yml** config file.

`vi .coveralls.yml`


```yml
repo_token: Y0urC0verallsRep0TokenGoesHere
```

Push your code to GitHub to trigger Travis and Coveralls.


#### Done. (Yes, its *That Simple*!)


<br />

### Other Options for JavaScript Code Coverage

- General JS: https://coveralls.io/docs/javascript
- Direct interface with Coveralls API: https://coveralls.io/docs/api 
(*beyond the scope of this tutorial*)


<br />
- - -

## More

### Further Reading

Both my JavaScript TDD Tutorials include sections on Code Coverage:

- QUnit: https://github.com/nelsonic/learn-qunit
- Mocha: https://github.com/nelsonic/learn-mocha

StackOverflow threads:

- http://stackoverflow.com/questions/1475520/unit-testing-code-coverage-do-you-have-100-coverage

Tutorials:

- http://boycook.wordpress.com/2013/09/17/javascript-coverage-with-istanbul-and-coveralls-via-travis-ci/

### Coveralls Pricing for "Private" (Closed Source) Projects

Like Travis CI, Coveralls is ***free for open source*** projects. <br />
Unlike Travis CI, Coveralls is "only"
[**$4.99** per month](https://coveralls.io/pricing) 
for a private repository! <br />
(**Travis**'s *entry-level* paid/private plan is 
[**$129** per month](http://travis-ci.com/plans)!)

### Next

- Code Complexity: http://en.wikipedia.org/wiki/Programming_complexity
- Why track complexity: http://www.databorough.com/Five-Reasons-to-Measure-the-Complexity-of-Your-Software.html
- Books to read: http://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read

> CodeClimate: https://codeclimate.com/github/signup
