#Using the waffle project management tool

##Adding a bug
Create an issue either in github or on waffle including a descriptive title and reproduction steps, sample code, and the browser & version you were using when you encountered the bug (if relevant). Label the issue "bug" and "icebox" (or, in waffle, label it "bug" and make sure it appears in the "icebox" stage).

##Suggesting future work
Similar to reporting a bug, add a card/issue for the work you'd like to see. Label it 'icebox' or be sure it comes up in the 'icebox' stage. Add one of the type labels if it makes sense.

##Grouping work into releases
As suggested work accumulates, it may be worthwhile to group logically related work into releases that can be completed as a unified venture of work. Consult with 
Foundations leadership, then create a github milestone to represent the release, then add the appropriate work to that milestone.

##Tracking your work in flight
As you pick up and complete work, be sure to move it to the appropriate stage as you go through the process of completing it. Stages are represented by labels in github, and columns on the waffle platform, and their meaning is defined below.

##Labels and their meaning
###Stages (blue, mostly)
- *icebox* : work that has been suggested, but has not been prioritized or is in some other way not yet actionable
- *backlog* : actionable work that is just waiting for the appropriate dev or designer to begin
- *design* : work that is in the design ideation/testing phase - if your work is in this phase you should be focusing on how your component looks and behaves, and making sure it can fill all of the required use cases
- *ready* : work that has been designed and gained the approval of the foundations council, but either does not exist in code yet, or the code that exists has not received attention wrt its interface/implementation details
- *development* : work that is in the process of being coded and documented
- *review* : coded work that needs to be reviewed in the form of a pull request
- *approved* : work that has been reviewed and approved in the form of a pull request, but has yet to be integrated into master and released
- *done* : work that has been released and is available on the master branch of ferrous

###Types (green, mostly)
- *new component* :  a new component
- *component review/improvement* : a change or extension to an existing component
- *discussion* : a placeholder for a discussion - no actionable work yet
- *quick win* : use this label for work that could probably be accomplished quickly and with minimal extenuating concerns (one person could do it and it will be pretty simple)
- *bug* : s***'s broken

###Other
- *respond* : tag work that has been reviewed in the form of a pull request and found lacking with this label to let the dev working on it know that it needs their attention
