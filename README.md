# CompareX

- #### Fork your own copy of the Repository

  The first thing you will want to do is fork [this](https://github.com/compare-X/CompareX) repository. What this mean, is that you get your own copy of this repository. You can then safely make changes to your own copy, and then later, you can submit your changes, and tell the PR lead(Primal) to combine (merge) the changes you made to the central/main repository. Here is a [tutorial](https://www.howtogeek.com/759384/how-to-fork-a-github-repository/#:~:text=To%20fork%20a%20repo%2C%20log%20in%20to%20your,been%20forked.%20Go%20ahead%20and%20click%20that%20button.) showing you how to do that

- #### Clone the Repository on your Local Machine

  The next thing you want to do is clone (make a copy) the compareX on your profile, to your local machine (Laptop, PC, MacBook). To do that,

  - Copy the link of your own compareX repository (the one you forked).
  - Open the folder you want to work on your machine.
  - Open your favourite editor(e.g Vscode).
  - Open the terminal.
  - run `git clone [Link to your copy of the compareX repository]`.
    > The link should look like this : `https://github.com/<your username>/CompareX`

- #### Configure the upstream

  Now that you have the local copy of compareX. Theres more than one developer contributing to the project, so you have to update your local copy very frequently. Therefore, you need to connect your local copy to the original repository. To do that :

  - go to your local machine terminal, in the project folder
  - run `git remote add upstream https://github.com/compare-X/CompareX.git`

- #### Commiting your changes

  Now, you can start making changes that relates to your issues and then commiting them. To do this, follow these instructions:

  - add the changes using `git add .` or any method(github desktop, VScode source control) that serves your needs.
  - add concise commit message.
    > e.g `git commit -m "adds signup button to the sign up page"`
  - run `git push origin`
    > Which pushes your changes to your online copy, after which you then open a pull request.

- #### Opening Pull requests

  Now that you have updated your online copy. You will need a way to inform the PR Lead handling the original repository that your contribution is ready. To do that, you open a Pull request, which simply means that you want them to combine(merge) your changes with that of the original repository. Because, what is the essence of making changes without the changes being merged right?

  To open a pull request, immediately after the last step (commiting your changes with push):

  - Head over to your github account. And click on your own copy of the compareX repository.
  - You will see the option to open a pull request.
  - Explain what your changes does.
  - Click the open pull request button and wait.

- #### Constantly update from upstream

  Now that you have forked the repository, you have cloned the repository and also set the upstream. To stay up to date and avoid conflicts. Before you edit anything, you need to update your local copy. Therefore, whenever you want to make any change, first run an update command like so:

  - In the directory of the project on your local machine
  - Open the terminal.
  - Run `git pull upstream main`
    > This will check for any changes that have been made to the original repository, it will then bring those changes to your local machine and merge (merge) the changes.

- #### Where to write your code
There is a folder in the compare-x folder called html. put your html files in that folder and your css in the folder called styles.
