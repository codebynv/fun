A chill, low-stakes GitHub playground. Use this repo to test PRs, break things on purpose, play with workflows, or practice Git commands without worrying about messing up actual project code.

What’s the point?
Try out Git & GitHub features (forks, branches, merge conflicts, actions).

Make your first open-source style pull request.

Experiment with small ideas or documentation edits in a safe sandbox.

Quick Start
Fork this repo to your own account.

Clone your fork locally:

Bash
git clone https://github.com//fun.git
cd fun
Link the main repo so you can pull updates later:

Bash
git remote add upstream https://github.com/codebynv/fun.git
Making a PR
Pull the latest code:

Bash
git fetch upstream
git checkout main
git merge upstream/main
Switch to a new branch:

Bash
git checkout -b my-test-branch
Make your edit (a typo fix, a small note in docs, or an experiment in achievements/).

Commit and push:

Bash
git commit -m "docs: add a quick note"
git push origin my-test-branch
Head over to GitHub and open a Pull Request against main.

Repo Layout
achievements/ – Drop files here if you're trying to trigger GitHub achievements or test commits.

CONTRIBUTING.md – Quick rules on keeping things clean.

Questions or stuck?
Open an issue or tag the maintainer directly in your PR.