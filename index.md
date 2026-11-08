---
description: Track changes with Git and GitHub, and make your first open-source contribution.
title: Use Git and GitHub | OpenCode School
image: https://opencode.school/og/exercise/use-git-and-github.png
---

[Open source on GitHub](https://github.com/opencodeschool/opencode.school)

[← All exercises](https://opencode.school/exercises)

You completed this exercise!

This exercise works best with OpenCode

Enroll in OpenCode School to get a student ID. Then paste the exercise prompt into OpenCode, and it will guide you through this project step by step.

[Enroll for free](https://opencode.school/)

Git gives you a way to see every change as it happens, so you’re not flying blind while OpenCode works on your project. GitHub gives you a place to safely store your work and collaborate with others. Learning these tools will give you more confidence on your own projects, and set you up to become an open-source contributor.

## What is Git?

[Git](https://git-scm.com) is a version control system that records every change to every file in a project. Each commit is a snapshot you can return to, so nothing is ever truly lost: if OpenCode makes a change you don’t like, you can revert it.

Git works entirely on your own machine. You don’t need an account, a server, or an internet connection to benefit from it. Even with no remote, Git gives you a complete history of your project.

## What is GitHub?

[GitHub](https://github.com) is a cloud platform for hosting Git repositories. It’s where you back up your work, share projects publicly or privately, and collaborate with other people. It’s also where most of the open‑source world lives.

The two are easy to mix up: Git is the tool that tracks changes on your machine, and GitHub is one popular place to host the repositories that Git creates.

## Get started with GitHub Desktop

[GitHub Desktop](https://desktop.github.com/) is a great GitHub interface for humans. It is also the easiest way to get from zero to a working Git setup, because it does three things in one install:

1. Installs Git on your machine.
2. Lets you sign up for GitHub or sign in to an existing account directly from the app.
3. Authenticates the Git CLI for you, so you can push to GitHub without setting up SSH keys or personal access tokens.

Once you’ve cloned or created a repository in GitHub Desktop, it also gives you a GUI for browsing your project’s history and visualizing exactly what changed in each commit. That visualization is the simplest way to review what OpenCode did to your files.

If you already have Git and a GitHub account, you can skip GitHub Desktop. The exercise still works.

## Install the gh CLI

If GitHub Desktop is GitHub’s interface for humans, the [`gh` CLI](https://cli.github.com/) is GitHub’s interface for agents. With `gh` installed, OpenCode can read issues, open pull requests, fetch PR diffs, leave comments, check CI status, and create repositories on your behalf, all without you leaving your session.

You’ll install it as part of this exercise and start using it from OpenCode right away.

## What you’ll do

- Install GitHub Desktop and the `gh` CLI, and add a `gh` rule to your global AGENTS.md
- Initialize a repository in a project folder so Git starts tracking changes
- Make commits: save snapshots of your work with a short description of what changed
- Review diffs: use GitHub Desktop or `git diff` to see exactly what OpenCode changed in your files
- Push to GitHub: back up your repository to the cloud, public or private
- Create a branch: try something experimental without affecting your main project

Once the basics are working, you can go further: write a `.gitignore` to keep clutter out of your repository, open a pull request, or explore your project’s commit history on github.com.

## Contribute to OpenCode School

Once you’re comfortable with commits, branches, and GitHub, you’re ready to make your first real open‑source contribution. This exercise includes an optional second path where OpenCode walks you through forking the [OpenCode School repository](https://github.com/opencodeschool/opencode.school), making a small improvement, and opening a pull request against it.

You don’t have to take this path to finish the exercise. If you’d rather stick with your own repo, that’s fine. But if you’ve ever wanted to contribute to open source, this is a low‑stakes way to do it. OpenCode will help you find a small change to make and walk you through every step, using `gh` to browse open issues and open the PR for you.

And remember: you don’t need any of this to help improve OpenCode School. Filing a GitHub issue about something confusing, broken, or missing is always welcome and doesn’t require Git at all. See [Contributing](https://opencode.school/contributing) for more.
