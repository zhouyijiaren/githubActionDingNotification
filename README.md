# DingNotification
- This is the Action of DingTalk Notification.
- Support the notify the Ding, when there is a push or pull request.
- It will show the diff.

## usage:
- can copy this to your github repo
- add DIFF_DINGDING_TOKEN to your repo's secrets
- modify the git in main.yaml (modify the below "README.md" to your path that you want to check the diff)
eg: git diff $COMPARE README.md > temp