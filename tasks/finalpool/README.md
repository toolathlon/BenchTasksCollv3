# Final Pool

Implemented tasks from `BenchTasksCollv3`, collected from the most recent commit of each developer branch that added new tasks. Development status for every new task is recorded in the Notion page `Task Tracker`.

## Contents

| Task | Source branch | Source commit |
| --- | --- | --- |
| gyy/tag-manager | gyy | 9612ffff |
| gyy/robots-handler | gyy | 9612ffff |
| haoze/media-organizer | haoze | e0072cf9 |
| junxian/social-connector | junxian_dev | 96bbc11b |
| xiaochen/health-monitor | xiaochen_dev | 20bfc734 |

Each folder mirrors the layout used on the developer branch (docs/, evaluation/, preprocess/, initial_workspace/, groundtruth_workspace/) and is a verbatim copy of the task files there.

## Selection rule (tasks/examples/example-task)

- `docs/task.md` and `docs/agent_system_prompt.md` must be non-empty and all English.
- `docs/user_system_prompt.md` must be all English when present.
- `evaluation/main.py`, `preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/` must exist.

A task is `implemented` when all of the above hold on its source branch, otherwise it is `implementing`.
