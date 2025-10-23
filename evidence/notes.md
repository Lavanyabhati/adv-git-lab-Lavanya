I chose rebase in Part A to maintain a clean linear history on main. 
During rebase, I encouraged a README.md conflict, which I resolved manually.
Later , I simulated a lost commit using reset and recovered it using reflog and a rescue branch.
This taught me that Git rarely loses any data.
One important note: after rebasing, always push with --force-with-lease, not --force to avoid overwriting.
