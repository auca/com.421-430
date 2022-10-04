# COM 421, Software Engineering
## Practice Task #2, Basic Branching and Merging in Git

### Requirements

1. Go back to the directory of the `vmath` local repo.

2. Create a new branch called `dev` and switch to it.

3. Through a series of commits, try to add a new `Vec3` class to your library. Continue practicing Test-Driven Development. This time you will have to write the test file on your own. Create the `Vec3Test.java` file in an appropriate test directory of your Gradle project.

4. Write all the tests. You may reuse code from the `Vec2Test.java` file.

5. Try to maintain your Git history on the `dev` branch similarly to what you were doing for `Vec2`. Create a skeleton of the `Vec3` class from the test file. Add implementation for each method one by one. Test each method by compiling and running test cases from the spec. Add each major (logically finished) part of your work to the repository history. Write good and consistent commit messages. Prefer the present tense in your [verbs](https://git.kernel.org/pub/scm/git/git.git/tree/Documentation/SubmittingPatches?h=v2.36.1#n181) in commit messages.

6. At the end, merge your `dev` branch into `master`. Ensure that the merge commit is created (you will have to find the options for the merge command on your own). Name the merge commit appropriately, outlining the new feature you were trying to add.

7. Tag the final version of your project as `v2.0` on the `master` branch.

8. Fast-forward the `dev` branch with the `master` branch for future work.

9. Push all the branches to your private `vmath` repo. Find out how to do that with one command on your own.

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
* `git branch`
* `git checkout`
* `git merge`

### Submission

TBD
