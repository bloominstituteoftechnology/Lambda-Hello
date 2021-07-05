# Lambda-Hello
Introductions to the Lambda Community

### Pull Request Challenge

This GitHub repository helps you practice the steps used to participate in open source code projects. You'll need to fork, clone, add, commit, push, and create a pull request to join in.

#### Git Configuration

First, let's verify that your global settings for Git are configured to the e-mail and username which you've used to sign up with GitHub. The following two commands should return your username and e-mail address:
`git config --global user.name` and `git config --global user.email`

If so, you are good to go! If, however, they return nothing, then you'll need to use the following commands to configure Git so the commits you push to GitHub properly reflect you as the author. For example, with the username "lisalovescode" and the e-mail "lisa1234@gmail.com"

```
$ git config --global user.name "lisalovescode"
$ git config --global user.email "lisa1234@gmail.com"
```

See also:

1. https://help.github.com/articles/setting-your-username-in-git/
2. https://help.github.com/articles/setting-your-commit-email-address-in-git/
3. If you do not want your e-mail address published with your commits, GitHub has a couple extra steps for you: https://help.github.com/articles/about-commit-email-addresses/

#### Challenge Details:

Follow these steps to contribute to this project:

1. Fork this repository to your personal GitHub account.
2. Clone the newly forked repository to your computer.
3. Create a new text file and name it based on your own name, such as "AndrewM.txt" (for a text file) or "EricaS.md" (if you're using Markdown). 
4. Edit your file. Introduce yourself by name. List three words that describe you. Write  a few sentences or a paragraph about your favorite hobby, your favorite animal, or another personal favorite suitable for sharing on a public site.
4. After writing, add your file to your project, commit, and push to your repository. 
5. Create a pull request back to the original LambdaSchool repository. 
6. Finish by adding a comment to your pull request. Call out your Project Manager by GitHub user-id (for example `@MyPM`, using a real GitHub account name) and mention the phrase "Core Hello Challenge".

### Branch Challenge

Use this repository to practice branching. You'll need to create a new branch, check it out, add, commit, push, and create a pull request. 

#### Challenge Details:

Follow these steps to create a personal branch and submit an "alternate reality" pull request.

1. In your cloned/forked repository, create a new branch named `alternate_reality`.
2. Edit the text file you created to describes yourself by listing three words that describe a someone completely unlike you. Edit your sentences to describe a hobby you don't participate in or another topic that reflects an alternate-reality version of who you are, suitable for sharing on a public site.
3. Use `git checkout` to switch between your `alternate_reality ` and `master` branches and confirm that your changes only appear in your branch.
4. Commit, and push your `alternate_reality` branch to your forked repository.
5. Create a pull request from your `alternate_reality` branch back to this repository. 
6. Finish by adding a comment to your pull request that call out your project manager by GitHub user-id and mentions the phrase "Branch Challenge"

### Extra Credit Challenge

Push further by practicing the way you amend an existing commit.

#### Challenge Details:

1. Making changes to either branch of your file and amend your commit. 
2. Push your amended commit to GitHub.
3. Leave a comment saying so on your pull request and call out your project manager by GitHub user-id.
