export Cron: crontab -l > myCrontab
import Cron: crontab myCrontab

-> use sudo for root crontab

myCrontab contains user Pi cronjob(Boot Time - Python Script)
myRootCrontab contains user root cronjob(Boot Time - GPS)