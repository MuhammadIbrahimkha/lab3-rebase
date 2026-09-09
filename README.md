# Lab 3: Rebase — Update a Feature Branch

Starter file:
- `health_check.py` — base program on `main`.

Follow the tasks in the assignment sheet:
1. Create `feature-health` from `main`.
2. Make one small change to `health_check.py` and commit it. Make another small change and commit it.
3. Switch to `main`, make a small change (simulating another developer), and commit it.
4. Switch back to `feature-health`.
5. Run `git rebase main`.
6. If there is a conflict, resolve it and run `git rebase --continue`.
7. View the final history with `git log --oneline --graph --all`.

Tip for instructors: if you want to guarantee a rebase conflict, have both the `main` commit and one of the `feature-health` commits edit the same line (e.g. the `print("Status: Healthy")` line).
