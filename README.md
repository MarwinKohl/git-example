# git-example

hello commit

## What are the benefits of commits?

* You can see what has been changed inside of a Git repository.

## Is there another way to verify a commit was created?

* Through Github, you can view a commit.

## How to check if a file is tracked and if not, track it?

* With "git-status", and if not then you can use the command "git add".

## In which situation should you use `git diff`?

* Diffing is a function that takes two input data sets and outputs the changes between them. git diff is a multi-use Git command that when executed runs a diff function on Git data sources. These data sources can be commits, branches, files and more.

## How do you create a patch wit `git diff`?

1. Generate the patch: git diff > some-changes.patch.
2. Apply the diff: Then copy this patch to your local machine, and apply it to your local working copy with: git apply /path/to/some-changes.patch. And that's it! The changes are now in your working copy and ready to be staged/commit/pushed.
