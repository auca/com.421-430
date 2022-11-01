# COM 421, Software Engineering
## Practice Task #3, Distributed Git Workflows

### Requirements

Try maintaining a Kanbas-like board on GitHub to track tasks and assignments. This part will not be graded in this lab, but we strongly encourage you to try doing things similarly with Projects and Milestones as the instructor did during the practice classes.

1. Go back to the directory of the `vmath` local repo.

2. Switch to the `dev` branch and make any minor commit on it (add credits to the `Readme.md`). Push the code to GitHub.

3. Pretend that you work with another developer in a centralized way. It means you share code with another developer through the central repository (in our case, on GitHub).

4. Create one topic branch to add the `Vec4` class with its tests to the code base. Work on it, making several commits like you were doing for `Vec2` and `Vec3`. Pretend you are developer #1.

5. In a different environment (terminal, IDE, Code Editor), clone the existing code `vmath` from GitHub and switch to the `dev` branch. Pretend you are developer #2.

6. Create a topic branch to add `cross()` method to calculate a cross product to `Vec3` with the test to the code base.

7. Merge code locally from the topic branch to `dev` and push `dev` to GitHub as developer #2.

8. Pull code to `dev` from GitHub with developer #1 changes, merge the topic branch to `dev` locally and push `dev` to GitHub as developer #1.

9. Pull code to the `dev` branch as developer #2. Ensure that both devs have `dev` in sync.

10. As developer #1, merge `dev` to `master` (or `main`). Push `main` to GitHub.

11. Tag the final version of your project as `v1.2.0` on the `master` branch. Then, push the tag to GitHub.

12. Fast-forward the `dev` branch to the `master` branch for future work. Then, push `dev` to GitHub.

13. Pull `master` and `dev` as developer #2. Ensure that both developers are in complete sync.

14. ...

### Managing a Project History with Git

* <https://git-scm.com/book/en/v2>

### Essential Git Commands to Use

* `git init`
* `git clone`
* `git add`
* `git status`
* `git commit`
* `git log`
* `git tag`
* `git push`
* `git pull`
* `git branch`
* `git checkout`
* `git switch`
* `git merge`

### Submission

TBD
