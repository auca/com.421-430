# COM 421, Software Engineering
## Practice Task #1: Git Basics

### Requirements

1. Download the source [file](https://gist.github.com/toksaitov/51441df88c9de21585c28a6e1f0ce8a8).

2. Create an empty directory named `vmath` outside of your course repo.

3. Navigate to the newly created directory.

4. Initialize both a new Gradle project and a Git repository. Follow the steps outlined below:

Maintain a repository for a project called `vmath`, which is a graphics math library. Initially, this library will contain just one class named `Vec2` that represents a 2-D [vector](https://docs.google.com/presentation/d/1Z3FYkQ29-txCH9qU3KcUc4RoZugBOK-0dZIX1i3TEno/edit?usp=sharing). In future labs, we will introduce more classes. Start by creating a README file that describes the library. Next, set up a Gradle project to automate building and testing the library. Add a test specification file with unit test cases for the `Vec2` methods. Generate the `Vec2` class from the specification file with methods left unimplemented. Implement each method one by one and test them by compiling and running the test cases from the spec. Commit each significant and logically finished segment of your work to the repository's history. Ensure that you write clear and consistent commit messages. Tag the final version of your project as `v1.0.0`. Finally, create a new GitHub repository on your account named `vmath` and push your code there.

### Managing a Java Project with the Gradle Build System

* Initialize a new Gradle project: `gradle init`
* Remove compiled files: `./gradlew clean`
* Build the library: `./gradlew build`
* Run tests: `./gradlew test`

### Managing Project History with Git

* Refer to: <https://git-scm.com/book/en/v2>

### Submission

1. Set up a private `vmath` repository on GitHub.
2. Push the local `vmath` repo from your machine/server to this GitHub repository.
3. Incorporate the `vmath` GitHub repo as a subtree in your private course directory, naming it `lab-1`.
4. Submit a URL that directs to the latest commit of your private course repository on Canvas.
