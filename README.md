# curator role

Installs curator from pip and sets cron tasks for closing and removing old indexes. Can be installed on all ES nodes, will run only on master node. You can set `curator_delete_older_than` and `curator_close_older_than` to `false` to disable related cron tasks.

You can also set deletion by exceeding size with ```curator_delete_by_exceed_gb``` variable, and protect recent indices with ```curator_delete_by_exceed_gb_max_age_days``` value.
