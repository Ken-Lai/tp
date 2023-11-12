---
layout: page
title: Guo Yuheng's Project Portfolio Page
---

### Project: Fumblelog

FFumbleLog is a desktop productivity application used for managing contacts and events. The user interacts with it using a CLI, and it has a GUI created with JavaFX. It is written in Java, and has about 10 kLoC.
**Given below are my contributions to the project:**
 
* **Code contributed**: [DistractedCat](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/?search=distractedcat&breakdown=true)
## Contributions to the project

### Code contribution
* [Link to RepoSense](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/?search=kurtyjlee&breakdown=false&sort=groupTitle%20dsc&sortWithin=title&since=2023-09-22&timeframe=commit&mergegroup=&groupSelect=groupByRepos)

### Enhancements Implemented
* Added new command to add events
* Added ability to assign persons to events
* Added ability to unassign persons from events
* Added ability for events to be updated when there is a change in the assigned persons
* Update the `add_person` command to appropriately handle assigning and un-assigning of groups and persons.
* Update the `edit_person` command to appropriately handle assigning and un-assigning of groups and persons.
* Update the `delete_person` command to appropriately handle unassigning of persons
* Added utility methods for commands
* Added ability to check for valid dates
* Added UI view for expired events by displaying them in a different card
* Added test cases for event commands, parsers and model.
* Added test utils for MeetingBuilder, TypicalMeetings and TypicalPersons.

### Contributions to the Developer Guide (DG)

* Added use cases for UC01-UC08
* Added activity diagram and object diagram
* Update details on program flow

### Contributions to the User Guide (UG)
* Added documentation for
    * `edit_event` command, where the user can edit the details of an event.
    * `delete_event` command, where the user can delete an event.
    * Assigning, Un-assigning persons, where users can do through the `add_event` and `edit_event` commands.
* Updated documentation for
    * `add_event` commands, where I detailed how to add events with persons, and to unassign them from the event
    *  Time requirements and behaviors when users are creating an event, since the user can add events without start or end times.

* Provided cosmetic enhancements and updates to the user guide.
* Updated images for the user guide.
* Updated commands with clearer descriptions of FumbleLog behaviour.


### Contributions to team-based tasks
* Conducted code reviews for PRs.
* Provided feedback for PRs.
* Helped increase code coverage by adding test cases.
* Created issues to track bugs and enhancements.
* Helped with the documentation process.
* Coordinated sprints and code review.
* Fixed bugs and issues.

### Contributions beyond the project team
* Good moral support.
