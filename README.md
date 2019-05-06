# dragnet-driver

This is an underbaked, underdocumented repo containing runtime information for
running [Dragnet](https://github.com/joyent/dragnet) on production Manta log
files.  This exists for historical reference only.

The cron job runs using this entry:

    15 0 * * * /home/dap/dragnet-driver/bin/cron >> /home/dap/dragnet-driver/cron.log 2>&1

where:

- `/home/dap/dragnet-driver` is a cloned copy of this repo
- `/home/dap/dragnet-driver/cron.sh` is derived from `cron.sh.example`
