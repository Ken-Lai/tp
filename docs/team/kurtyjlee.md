---
layout: page
title: Kurt Lee's Project Portfolio Page
---

# Project: FumbleLog

FumbleLog is a desktop productivity application used for managing contacts and events. The user interacts with it using a CLI, and it has a GUI created with JavaFX. It is written in Java, and has about 10 kLoC.

## Contributions to the project

### Code contribution
* [Link to RepoSense](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/?search=kurtyjlee&breakdown=false&sort=groupTitle%20dsc&sortWithin=title&since=2023-09-22&timeframe=commit&mergegroup=&groupSelect=groupByRepos)

### Enhancements Implemented
* Added new command to edit events.
* Added new command to delete events.
* Added new command to assign groups to events.
* Added new command to unassign groups from events.
* Updated the `delete` command delete empty groups from events.
* Update the `add` command to appropriately handle assigning and un-assigning of groups and persons.
* Update the `edit` command to appropriately handle assigning and un-assigning of groups and persons.
* Added test cases for event commands, parsers and model.
* Added test utils for MeetingBuilder, TypicalMeetings and TypicalPersons.

### Contributions to the Developer Guide (DG)
* Added implementation details for tracking Events.
* Updated use cases for 
  * Events CRUD operations
  * Assigning groups
  * Unassigning groups
  * Find by groups.
* Added class diagrams and sequence diagrams.

### Contributions to the User Guide (UG)
* Added documentation for 
  * `edit_event` command, where the user can edit the details of an event.
  * `delete_event` command, where the user can delete an event.
  * Assigning, Un-assigning Groups, where users can do through the `add_event` and `edit_event` commands.
* Updated documentation for
  * `add_event` commands, where I detailed how to add events with groups.
  * `add` command, where I detailed how to add persons with groups.
  * `edit` command, where I detailed how to edit persons with groups.
  * `delete` command, where I detailed how to delete persons with groups.
* Provided cosmetic enhancements and updates to the user guide.
* Updated images for the user guide.
* Updated commands with clearer descriptions of FumbleLog behaviour.


### Contributions to team-based tasks
* Conducted code reviews for PRs.
* Provided feedback for PRs.
* Helped increase code coverage by adding test cases.
* Created issues to track bugs and enhancements.
* Helped with the release process.
* Helped with the documentation process.
* Coordinated sprints and code review.
* Fixed bugs and issues.

### Contributions beyond the project team
* Good moral support.
