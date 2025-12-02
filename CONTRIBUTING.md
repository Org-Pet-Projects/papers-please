# Contributing  to the Papers Please

Thank you for your interest in contributing! :tada:

This project brings together people who are interested in Java, eager to learn something new, solve real problems, and improve production-quality code. Because the project covers multiple areas — UI, infrastructure, microservices, and more - it is a great place to collaborate, grow, and apply engineering best practices.

### Table of Contents

* [Code of Conduct](#code-of-conduct)
* [Motivation and Purpose](#motivation-and-purpose)
* [How to Get Started](#how-to-get-started)
* [Choosing What to Work On](#choosing-what-to-work-on)
* [Creating Your Branch](#creating-your-branch)
* [Keeping Your Branch Updated](#keeping-your-branch-updated)
* [Submitting a Pull Request](#submitting-a-pull-request)
* [PR Best Practices](#pr-best-practices)
* [Code Review Process](#code-review-process)


### Code of Conduct

By contributing, you agree to follow our Code of Conduct.
We strive to maintain a friendly, supportive, and inclusive environment.


### Motivation and Purpose

Our goals:
- Learn collaboratively by exploring a variety of real-world topics:
  - UI development
  - Infrastructure and DevOps
  - Microservices and distributed systems
  - Performance, testing, design patterns 
  - AI :) 
  - and even more

- Improve real working code through contributions, reviews, and discussions.
- Solve meaningful problems together and help contributors grow their engineering skills.

If you are here to learn, teach, explore new areas, or sharpen your professional development skills - you're in the right place!

### How to Get Started

#### 1. Fork the Repository
Click **Fork** in the top-right corner of the GitHub page.

#### 2. Clone Your Fork
``` bash
git clone git@github.com:<your-username>/papers-please.git
cd papers-please
```

#### 3. Set Upstream Remote
``` bash
git remote add upstream git@github.com:Org-Pet-Projects/papers-please.git
```

### Choosing What to Work On
- Check the **Issues** tab.
- Look for labels such as:
  - `good first issue`
  - `backend`
  - `UI`
  - `documentation`
  - `infrastructure`
  - `bug`

- Leave a comment to claim an issue: *"I'd like to work on this."*
- Open new issues for bugs, ideas, or proposals.

This project encourages exploration, so feel free to pick areas you want
to learn (UI, infra, microservices, etc.).

### Creating Your Branch

Create a feature branch before making changes:

``` bash
git checkout -b feature/my-change
```

Use the following patter for the branch names:
- `feature/PP-{issue number}-{issue-subject}`
- `bugfix/PP-{issue number}-{issue-subject}`
- `docs/PP-{issue number}-{issue-subject}`
- `infra/PP-{issue number}-{issue-subject}`

### Keeping Your Branch Updated

``` bash
git fetch upstream
git rebase upstream/main
```

This keeps history clean and linear.


### Submitting a Pull Request

#### 1. Push your branch:

``` bash
git push origin feature/my-change
```

#### 2. Open a **Pull Request**.

Fill in the template:
- What problem it solves
- Summary of changes
- How to test it
- What new you have learned (provide useful sources of knowledge)

### PR Best Practices

-   Keep the PR focused on one topic.
-   Prefer **a clean, linear commit history**.
-   Squash noisy commits before review.
-   Mark as **Draft** if still in progress.

### Code Review Process

Maintainers will: 
- Review your PR 
- Provide feedback
- Approve or request changes 
- Merge the PR once ready

## Thank You! :raised_hands:
