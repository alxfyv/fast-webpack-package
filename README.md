# fast-webpack-package
Fast Element webpack

This package was created as a repository for Fast-Element Web Components to be used in constructing custom elements for the Sessions Table on familyhistoryconferencenwa.org/2021-session.

The "table" is a matrix of sessions across classrooms at set time slots throughout the day of an annual genealogy conference put on by a Northwest Arkansa genealogy nonprofit group. For example, at the 2019 conference there were 5 timeslots ("rows") during the day and sessions conductedi in 7 rooms ("columnms") at the conference site. Each "cell" in the table contains four elements: 1 each for the speaker's name and the session topic title, 1 for the room capacity, and 1 for a running, live counter of the number of attendees registered for that session.

In addition, in each cell are 3 further containers: 1 for the several-paragraph session-topic description, 1 for the several-paragraph speaker's bio, and 1 for the speaker's headshot. The scheme is that upon mouseOver the session topic title or the speaker's name, a modal dialog will show with the appropriate further information.

The 2021-Session page will be dynamically constructed on each page load from data in a backend data base.

This repository will house the Fast-Element, custom elements necessary to the scheme's implementation.
