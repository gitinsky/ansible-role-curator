# curator role

Installs curator from pip and sets cron tasks for closing and removing old indexes. Can be installed on all ES nodes, will run only on master node. You can set `curator_delete_older_than` and `curator_close_older_than` to `false` to disable related cron tasks.
