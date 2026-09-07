# Finalpool - implemented tasks

Tasks that satisfy the requirements defined in `tasks/examples/example-task`:
- `docs/task.md` - non-empty, all English
- `docs/agent_system_prompt.md` - non-empty, all English
- `docs/user_system_prompt.md`
- `evaluation/main.py`
- `preprocess/main.py`
- `initial_workspace/`
- `groundtruth_workspace/`

## Review performed

All 14 developer branches of `BenchTasksCollv3` were reviewed at their **most recent
commit**. Those commits touched 28 task folders: 22 of them satisfy every
requirement above (implemented), 6 do not yet (implementing).

## Already in the pool before this review (5 tasks)

- price-tracker (fan-dev)
- shipment-tracker (junteng_dev)
- expense-tracker (ruige)
- error-tracker (xiaochen_dev)
- task-scheduler (yuxuan-dev)

One further task, `storage-manager` (zhaochen), was already present in the pool,
so 22 tasks were added by this review - 27 implemented tasks in total.

## Implemented (22 tasks added by this review)

- loyalty-program (fan-dev)
- discount-calculator (fan-dev)
- tag-manager (gyy)
- sitemap-generator (gyy)
- robots-handler (gyy)
- media-organizer (haoze)
- streaming-service (haoze)
- customer-feedback-processor (jl_dev)
- inventory-management (jl_dev)
- customer-portal (junteng_dev)
- help-desk (junteng_dev)
- social-connector (junxian_dev)
- survey-builder (lv)
- analytics-dashboard (lv)
- web-crawler (ruige)
- log-analyzer (ruige)
- cache-optimizer (wenshuo-dev)
- scheduler (wenshuo-dev)
- status-checker (xiaochen_dev)
- health-monitor (xiaochen_dev)
- sync-service (yuxuan-dev)
- certificate-manager (zhaochen)

## Still implementing (6 tasks - not added by this review)

- currency-converter (junxian_dev) - docs/task.md contains Chinese
- territory-manager (lueyang-dev) - missing preprocess/main.py
- client-portal (lueyang-dev) - missing initial_workspace
- insights-engine (lv) - agent_system_prompt.md contains Chinese
- audit-logger (yuzhen-dev) - agent_system_prompt.md contains Chinese
- resource-monitor (yuzhen-dev) - agent_system_prompt.md contains Chinese

## Tracking

Every one of the 28 reviewed tasks is recorded on the Notion `Task Tracker` page
as `<task name> | <implementor> | <status>`.
