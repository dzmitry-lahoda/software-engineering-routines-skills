
# Input

outpuf of domain analyss of each code piece

## When not to use

When there is more than one commit to rebase.

#  During

- Get whol conclict into local file.
- Identify each conflicting commit and why it was made.
- Idenfity if each conflict is conflict of code, but not of opposite semantics.
- Consider how to merge semantics together.
- lock files just use earlier


output whole plan and wait for apporival

rebase on worktree
ask for lint and tests to run,
make run over CI via PR if possible.

check that each functional detail is in place in new commmit, if not document what changed
in this case ask for confirm

wait confirm to force push into proposed pach or send new one.

any features on master added since branch
  created which can shortcut impl of currenct branch? less code
