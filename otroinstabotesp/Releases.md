| Version | Description                                        |
|:-------:|:---------------------------------------------------|
| 0.5.21  | Verify configuration before start a bot            |
| 0.5.22  | Stop instabot if we have nonexistent tag in config |
| 0.5.23  | Fixed a bug: `like_followers_per_run` functionality didn't work |
| 0.5.24  | Bot stops working if like action is banned. Bot can be started again with `like_per_run: 0` configuration setting |
| 0.5.25  | Show proper error message if we have issues in getting number of user's followers |
| 0.5.26  | Show proper error message if we have issues in verifying media before commenting it |
| 0.7.0   | Refactor class InstaBot: clean a lot of unused variables, fix some obsolete interdependencies |
| 0.7.1   | Make login to IG simpler. Should fix issues with login |
| 0.7.2   | Actions *_per_run depend on time the bot works (issue 2574) |
| 0.7.3   | Add Telegram handler package |
|         | Fix issue with posts commenting (issue 2578) |
| 0.7.4   | Bot can run many days without interruption (issue 2402) |
| 0.7.5   | Skip chosen media for commenting if comments are disabled on it |
| 0.7.6   | Stop the bot if we sent "Too many requests to Instagram" (issue 2582) |
| 0.7.7   | Notify about bot's settings when bot starts (issue 2568) |
| 0.7.8   | Fix issue with message output when IG banned account due to "Too many requests" |
