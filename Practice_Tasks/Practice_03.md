# COM 421, Software Engineering
## Practice Task #3, Distributed Git Workflows (Centralized Workflow)

### Requirements

Try maintaining a Kanban-like board on GitHub to track tasks and assignments. Although this part will not be graded in this lab, we strongly encourage you to use Projects and Milestones as demonstrated by the instructor during the practice classes.

1. Navigate back to the directory containing your local `vmath` repository.

2. Switch to the `dev` branch and make a minor commit (e.g., add credits to the `Readme.md`). Then push the changes to GitHub.

3. Collaborate with another developer in a centralized manner, meaning that you will have to share code through a central repository (in our case, on GitHub). Decide who will play the role of the Developer #1 and Developer #2.

4. As Developer #1, add the `Vec4` class with its corresponding tests to the codebase. Work on the class, making several commits, as you did for `Vec2` and `Vec3`.

5. As Developer #2, clone the `vmath` repository from GitHub and switch to the `dev` branch. Create a topic branch to add a `triple()` method that calculates the [triple product](https://en.wikipedia.org/wiki/Triple_product) of three `Vec3` instances. Implement the method and write its tests. Merge the changes from the topic branch to `dev` locally and then push `dev` to GitHub.

6. As Developer #1, pull the updated `dev` branch from GitHub, merge it with your changes if necessary. After that, merge `dev` into `master` (or `main`, if that's the name of your primary branch). Tag the final version of your project as `v1.2.0` in the `master` branch. Fast-forward the `dev` branch to match the `master` branch in preparation for future work, and then push all the branches with tags to GitHub.

8. As developer #2, pull both `master` and `dev` to ensure that the branches are fully synchronized between both developers.

### Managing Project History with Git

* <https://git-scm.com/book/en/v2>

### Submission

Both developers (#1 and #2) will have to do the following in their private course repository:

1. Add the `vmath` GitHub repository as a subtree within your private course directory, naming it `lab-3`.
2. Submit the URL pointing to the last commit of your private course repository on Canvas.
