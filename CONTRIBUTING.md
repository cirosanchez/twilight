# Twilight Contribution
Here at Flyte we're happy to receive all your contributions to all of our open source projects.

## Forks
In GitHub, in order to make a pull request with your code implemented, you need to create a fork of twilight in your account,
in order for us to check faster the pull requests, use a personal account, not an organization. This is because of the modifications we can do
to your pull request, like grammar, encapsulation issues or general code modifications to the PR. If you use an
organization account, the PR won't be modifiable for us, making this **mandatory** manual merge and modifications. 

## Requirements
To get started in your Pull Request journey, twilight has some requirements for your machine:

* [Git](https://git-scm.com/): In order to clone your fork, you need to use git in your machine.
* [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html): twilight uses JDK 17 as the target release.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/): Knowing that twilight is a Kotlin API, our contributors normally use IntelliJ IDEA to develop twilight functions as the official Kotlin IDE from JetBrains.

## How to make a fork twilight
As mentioned before, a fork is needed in order to make a pull request to any GitHub repository. So, firstly we have to set up the fork in our personal account.

### Creating the fork in your personal account 

In the main page of twilight in GitHub, we need to click the `Fork` button:

![forkbutton](https://i.imgur.com/HWIlOoe.png)

After clicking this button we will be redirected to a special page to create a Fork, in this page, please, use a personal account, not an organization.
After selecting the owner's account, click `Create Fork` button at the bottom right section.

![createfork](https://i.imgur.com/GnFUQYp.png)

After creating the fork we will be ready to code our contributions.

### Code editing
After creating our fork, we will need to clone it into our machine in order to have a proper coding session. This can be accessed in two ways, via the web URL and the GitHub implementation in IntelliJ IDEA.

**Web URL:**

![weburl](https://i.imgur.com/9URYAWm.png)

**IntelliJ GUI:**
![intellijgui](https://i.imgur.com/WHAPaQl.png)

Both of them will do the same task, clone the repository.

After cloning the repository, you'll be ready to go to write some code.

### Code conventions
In order to make the code is legible for all contributors, you could take some of this recommendations:

* Use **gg.flyte.twilight** package in all of your contributions.
* Debug totally your code before requesting a merge.
* Comment all your code in order to make it more readable for pull requests reviewers, even make some javadocs.
* Follow some **SOLID** principles: [DigitalOcean SOLID](https://www.digitalocean.com/community/conceptual-articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design).

### Testing
In order to test your new additions to twilight, please, do not use main folder. **USE TEST FOLDER** as is being used in the repository.

### Commiting
After testing all your new functions and debugging it, a commit should be the way to go for each function implemented. Please don't name this like "a", "commit", "events", name it with a description of the actions you made, for example: *"Added CONTRIBUTING.md"*, *"Fixed Grammar errors in CONTRIBUTING.md"* or *"Improved performance in Redis.kt"*. It'd be recommended to provide a description of your commit, noting some of the additions made.

## Pull Request Creations
After commiting and pulling your contributions in twilight, your personal fork should see like this: