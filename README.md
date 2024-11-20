
## About the project

This project is a collaborative effort between [Shawn](https://github.com/toastyplains) and [Myself](https://github.com/michael-kudrik) for our principles of programming language final project. We will be using python with libraries such as `numpy`, `pandas`, etc. 

### Dataset used 

We will be using the following dataset: 
[https://archive.ics.uci.edu/dataset/162/forest+fires](https://archive.ics.uci.edu/dataset/162/forest+fires)

## Branches


### `main` branch

- From the main branch, run:

```bash
git checkout main
```

- Push the branch to GitHub:

```bash
git push -u origin main
```

This is the main branch and should not be directly edited. Instead refer to working branch below. Main branch can be pushed to when something is finalized or close to. 

### `working` branch

- From the main branch, run:

```bash
git checkout working
```

- Push the branch to GitHub:

```bash
git push -u origin working
```

This branch will be dedicated to the current work being preformed.

### `feature` branches:

You can further create "feature branches" for each task you're working on.
This will help break down work into smaller, manageable pieces.

**Example:**

- If you're working on calculating the mean of a dataset:

```bash
git checkout -b feature/mean
```

- If Mike is working on something of his own he can do this:

```bash
git checkout -b feature/mikeswork
```

After completing a feature, you both can create a pull request (PR) to merge the feature branch back into the respective main branch (`feature` or `working`). See [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request)

