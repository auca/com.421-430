# COM 421, Software Engineering
## Bonus Project: Building an Online Judge Prototype

![Figma Wireframe](https://i.imgur.com/4Qg8Qiw.png)

### Overview

This task involves creating a prototype for an [Online Judge System](https://github.com/toksaitov/com-421-course-project/wiki) discussed at the end of the semester. The system's primary function is to evaluate student code submissions for programming problems. The key challenge is to implement an isolated environment using either virtualization, containerization (or other new technologies like Wasmer) for safely executing student-submitted code.

### Requirements

1. Build a proof-of-concept Online Judge System. This system should be capable of receiving code submissions, executing them in a secure, sandboxed environment, and returning the results.

2. **Frontend**:
   - Develop a single web page featuring:
     - A hardcoded programming problem with a description and test cases.
     - A submission form allowing students to submit their code solutions.

3. **Backend**:
   - Implement an isolated execution environment using a technology of your choice (virtualization, containerization, etc.).
   - The backend should compile and run the submitted code in this isolated environment.
   - Ensure that the execution process is secure and cannot affect the host system or other submissions.

4. **Result Reporting**:
   - The frontend should display the execution results concisely on the same page as the submission form.

### Notes

* User accounts and persistent data storage are not required in this prototype.

* You are free to choose any programming languages, frameworks, and tools that best suit the project's needs. Emphasize technologies that facilitate rapid development and easy implementation of the required features.

* Don't forget to put a `Readme.md` file in the root of your project folder. This file should contain instructions on how to setup and run your project.

### Submission Guidelines

1. In your private course repository on GitHub, put all your files including the `Readme.md` with information on how to run your project into a single folder named `project`.
2. Push your code to this repository.
3. Submit the URL pointing to the last commit to Canvas before the deadline.
