<a name="top"></a>

<div align="center">
  <h1 align="center">How To Contribute</h1>
</div>
<br />

<details>
  <summary>Agenda</summary>
  <ol>
    <li><a href="#1-fork-the-repository">1. Fork The Repository</a></li>
    <li><a href="#2-clone-your-fork">2. Clone Your Fork</a></li>
    <li><a href="#3-set-up-the-upstream-remote">3. Set Up the Upstream Remote</a></li>
    <li><a href="#4-create-a-new-branch">4. Create a New Branch</a></li>
    <li><a href="#5-make-your-changes">5. Make Your Changes</a></li>
    <li><a href="#6-commit-your-changes">6. Commit Your Changes</a></li>
    <li><a href="#7-push-your-branch-to-github">7. Push Your Branch to GitHub</a></li>
    <li><a href="#8-open-a-pull-request">8. Open a Pull Request</a></li>
    <li><a href="#9-respond-to-review-feedback">9. Respond to Review Feedback</a></li>
    <li><a href="#10-keep-your-fork-up-to-date">10. Keep Your Fork Up-to-Date</a></li>
    <li><a href="#11-celebrate-your-contribution">11. Celebrate Your Contribution!</a></li>
  </ol>
</details>



# 1. Fork The Repository

Before making any modifications, you must first fork the repository to your own GitHub account.

1. Visit the [repository page](https://github.com/johannesbausch/repository-kickstarter).
2. Click on the "Fork" button in the top-right corner.
3. GitHub will create a copy of the repository in your account.

<div align="right">
  
  [Jump to Top](#top)

</div>
<br />



# 2. Clone Your Fork

1. Open a terminal on your computer and run the following command to clone the repository:
   ```shell
   git clone https://github.com/your_username/repository-kickstarter.git
   ```
2. Replace your_username with your GitHub username.
3. Navigate into the project directory:
   ```shell
   cd /path/to/your/repository-kickstarter
   ```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 3. Set Up the Upstream Remote

To keep your fork up to date with the original repository, you need to add an "upstream" remote.

1. Run the following command in the terminal:
   ```shell
   git remote add upstream https://github.com/johannesbausch/repository-kickstarter.git
   ```
2. Verify that the upstream remote has been added:
   ```shell
   git remote -v
   ```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 4. Create a New Branch

To keep your changes organized and distinct from the main codebase, create a new branch.

1. First, ensure you're on the main branch:
   ```shell
   git checkout main
   ```
2. Generate a new branch and switch to it using the following command:
   ```shell
   git checkout -b feature/your-desired-feature
   ```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 5. Make Your Changes

You’re now ready to modify the code. Open the project in your preferred code editor, make the necessary changes, and save your work.

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 6. Commit Your Changes

Once you’ve made your changes, it’s time to commit them to your branch.

1. To see which files have been modified, run:
   ```shell
   git status
   ```
2. Stage your changes:
   ```shell
   git add .
   ```
3. Commit your changes along with a clear and descriptive message:
   ```shell
   git commit -m "Added something"
   ```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 7. Push Your Branch to GitHub

Upload your changes to your forked repository on GitHub:
```shell
git push origin feature/your-desired-feature
```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 8. Open a Pull Request

Once your changes are pushed to your fork, it's time to create a pull request (PR) to the original repository.

1. Visit the [original repository](https://github.com/johannesbausch/kicksterter-repository) on GitHub.
2. Click the "Compare & pull request" button.
3. Review your changes to make sure everything is correct.
4. Provide a clear and descriptive title and description for your PR.
5. Click "Create pull request."

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 9. Respond to Review Feedback

After submitting your pull request, a code style check will run automatically, and the repository maintainers may review your code and request changes.

If any changes are requested, update your branch locally, commit the changes, and push them to your fork. The pull request will automatically reflect the latest updates.

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 10. Keep Your Fork Up-to-Date

To keep your fork synchronized with the original repository, make sure to regularly update it.

1. Fetch the latest changes from the upstream repository by running:
   ```shell
   git fetch upstream
   ```
2. Merge the upstream changes into your local main branch using the following command:
   ```shell
   git checkout main
   ```

   ```shell
   git merge upstream/main
   ```

3. Push the updated main branch to your fork:
   ```shell
   git push origin main
   ```

<div align="right">
  
  [Jump to Top](#top)
  
</div>
<br />



# 11. Celebrate Your Contribution!

After your pull request is merged, you’ve successfully contributed to an open-source project!

**🙏 Thank you for your service!**
