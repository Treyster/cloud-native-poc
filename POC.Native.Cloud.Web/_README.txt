The following will serve as a source of record for the markdown

= Disclaimer

+ This is express written for Raytheon as a guide to moving to 
  cloud native apps.  There are cases where I used frameworks that
  are not currently available to the Raytheon team.  There may be 
  alternatives the team uses already in place.  I used simply used
  the ones I'm familiar with.

= Patterns and Practices

+ I've read that developers make the mistake when moving to the cloud
  by simply breaking up the monolith, resulting in microliths.  To 
  truly tap into the power of the cloud platform, greenfield project
  should use the patterns outlined in this solution.

= Testing 

+ You'll notice unit and integration tests are separated out.  This is
  to allow the unit tests to always be run upon build.  Integration
  tests are to be run on demand
+ 

= CI/CD/CT

+ So for CI/CD I'm not using Concourse here... didn't want to setup the
  VM standalone.  I decided to use werker (http://www.wercker.com/)

= Aspect Oriented Programming

= Test Driven Development