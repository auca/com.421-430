# COM 421, Software Engineering
### Practice Task #5, Building a Project with Application Lifecycle Management Software

![Practice 5](http://i.imgur.com/kV03AFB.png)

#### Task Requirements

Build a project for a customer in two iterations by using an Agile methodology
and by utilizing an ALM system.

The ALM system that we are using this year is Microsoft Visual Studio Team
Services (VSTS). The Agile framework that you should try to practice is Scrum.

The practice task serves as a preparatory step for the course project.

#### Working With Customer's Requirements

1. Create a personal account at [visualstudio.com/team-services](https://www.visualstudio.com/team-services).
2. Create a new agile project in VSTS.
3. Set the version control system to Git.
4. On the _Work_ tab copy the provided user stories into the project management
   system. Group them as features.
5. Based on the user stories create a storyboard/s for the future application.
   Link the storyboard/s to the user stories.
6. Split user stories into self-contained tasks. Make the tasks to be child
   elements of the user stories.
7. Order the tasks with user stories by importance in your backlog.
8. Set capacity in hours for every user (just you) for a sprint.
9. Select the top tasks from the backlog to the first sprint based on rough
   estimations.
10. Start your work on the first sprint.
11. Use the burn down chart to help you adjust the amount of work and track your
    progress.
12. Use the experience and data from the previous iteration to go into the
    second sprint.

#### Testing

1. Create a separate project for unit tests.
2. Consider using the Test-First approach in development.
3. Fake the UI interactions with system dialogs in your tests.
4. Maintain the code coverage by your tests at least at 70%.

#### Using Continuous Integration

1. Create a build definition on the Build and Release tab in VSTS.
2. Set it up to trigger a build and test steps for every commit to the
   development branch.

#### Managing Sources

1. Use local feature branches for every work item from the project.
2. Merge feature branches to the local development branch on task completion.
3. Push the development branch to the remote repository on VSTS.
4. Merge to the stable master branch only through a pull request.
5. Configure the master branch policies to force at least one code review, a
   successful CI build, and a linked work item for every pull request.

#### Submitting Your Work

1. Add the instructor's account as a stakeholder to your project in VSTS.
2. Do not block access to the project after the deadline.

#### Deadlines

You will have time untill the end of the semester. In labs you have to
work on a text editor application `Focus`. For the course project, you have to
build an image editing application. Sample sources can be found
[here](https://drive.google.com/file/d/1hYatyQgd6-leyOpC0xCJRDhgugJI6E9p/view?usp=sharing).
Sample storyboards can be found [here](https://docs.google.com/presentation/d/1KObVe2k4sbw-d7WPFo3S0d0127ryF11CTV3H2mo3mUc/edit?usp=sharing).

---

#### Sample User Stories

##### General Recommendations

Development team should be able to work together efficiently. The VCS, CI, IDE,
solutions, repos should be setup properly to work with VSTS. The application
should be well-tested.

##### The Application Window

As a user I would like to have one window to edit text files. The window should
include just the text area to allow me to focus on my work. The window should be
centered as I don't like wasting time positioning the window. The initial window
size should be set to some sane value. The window should only contain the name
of the program. The program icon should be set to something reflecting the
application's nature.

##### Basic Operations

As a user that would like to edit text documents. I would like to open them and
preview in the editor. As I don't want to have buttons on the main interface as
a distraction, I should be able to open files either with the `CTRL+O` key
combination (common to any document editing programs), or by dragging and
dropping the file into the program. I would like to see error messages in case
the program fails to open a file.

As a user I would like to save my work or duplicate a file under a different
name. As I don't want to have buttons to open or save files as they look
distractive, I should be able to save a file by pressing the `CTRL+S` key
combination. Before exiting from the program, I would like to get a prompt
whether I want to save uncommitted changes with buttons: to save changes and
exit, don't save and exit, or go back to the program. The program should warn
me about any file operation errors.
