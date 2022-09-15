# COM 421, Software Engineering
### Practice Task #1, Git Basics

#### Requirements

1. Get the following source [file](https://gist.github.com/toksaitov/51441df88c9de21585c28a6e1f0ce8a8).

2. Create an empty directory `vmath` (!) outside your course repo.

3. Go into the newly created directory.

4. Initialize a new Gradle project and a new Git repository. Do the work
 outlined below:

Try to maintain a repository for a project of a graphics math library called `vmath`. For now the library will contain just one class called `Vec2` representing a 2-D [vector](https://docs.google.com/presentation/d/1Z3FYkQ29-txCH9qU3KcUc4RoZugBOK-0dZIX1i3TEno/edit?usp=sharing). In future labs we will add more classes. Imagine that you are working on the project from the beginning. Start by creating a Readme file with a simple library description. Next, create a Gradle project to automate the process of building and testing the library. Add a test specification file with unit test cases for `Vec2` methods. Create the `Vec2` class itself from the specification file with empty methods without implementation. Add implementation for each method one by one. Test each method by compiling and running test cases from the spec. Add each major (logically finished) part of your work to the repository history. Tag the final version of your project as `v1.0`. Create a new GitHub repository on your account called `vmath`. Push the code there.

#### Managing sources with the Gradle build system

* Create a new Gradle project `gradle init`
* Remove compiled files `./gradlew clean`
* Build the library `./gradlew build`
* Run tests `./gradlew test`

#### Essential Git Commands

* `git init`
* `git clone`
* `git add`
* `git status`
* `git commit`
* `git log`
* `git tag`
* `git push`
