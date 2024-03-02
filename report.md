# Report for assignment 4

## Project

Name: Openverse

URL: https://github.com/WordPress/openverse

Openverse is a platform and search engine for openly licensed media content, such as  GPL-compatible images, audio, and more.

## Onboarding experience

We had not worked with the project beforehand. The onboarding was quite a bit more time consuming, but that is also in part due to the nature of the project.

If you changed the project, how did your experience differ from before?

## Effort spent

For each team member, how much time was spent in

1. plenary discussions/meetings;

2. discussions within parts of the group;

3. reading documentation;

4. configuration and setup;

5. analyzing code/output;

6. writing documentation;

7. writing code;

8. running code?

For setting up tools and libraries (step 4), enumerate all dependencies
you took care of and where you spent your time, if that time exceeds
30 minutes.

Benjamin:
Felix:
Isadora:
Jonatan:
Rasmus: 2, 1, 4, 3, 4, 5, 1, 1

## Overview of issue(s) and work done.

Title: Refactor and improve VTag component

URL: https://github.com/WordPress/openverse/issues/3190

The changes include forwarding all props to the inner VButton. Using slots instead of props for content. Accessible labels as well as testing for VTags.

This affects the following components: VTag, VMediaTags, VButton, and VMediaTag.

## Requirements for the new feature or requirements affected by functionality being refactored

Optional (point 3): trace tests to requirements.

## Code changes

### Patch

(copy your changes or the add git command to show them)

git diff ...

Optional (point 4): the patch is clean.

Optional (point 5): considered for acceptance (passes all automated checks).

## Test results

Overall results with link to a copy or excerpt of the logs (before/after
refactoring).

## UML class diagram and its description

![UML class diagram](VtagUML.png)

### Key changes/classes affected

Optional (point 1): Architectural overview.

Optional (point 2): relation to design pattern(s).

## Overall experience

What are your main take-aways from this project? What did you learn?

How did you grow as a team, using the Essence standard to evaluate yourself?

Optional (point 6): How would you put your work in context with best software engineering practice?

Optional (point 7): Is there something special you want to mention here?
