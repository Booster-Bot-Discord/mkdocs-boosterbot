# Q. How to setup Booster Bot?

Booster Bot needs basically only 1 thing:
System channel enabled and "Send message when someone boosts this server" enabled in your server settings.

Make sure bot has read & send message permissions along with embed links, so that bot can send beautiful Greet Messages when someone boosts and track them for you.

Refer to this [YouTube video](https://youtu.be/FdyeBrE7VHo) for basic bot setup.

**OR** checkout docs for [#getting started](/setup) command.

---

# Q. Is there any way to give special role to double-boosters?

Yes, Booster Bot tracks each boost and keeps count of boost for each member and you can use `bb lvl-role` to setup boost level roles.
Check `bb help lvl-role` to know more about level roles OR refer the [#level role docs](/commands/boosters/lvlrole/).

However, no one can detect if someone removed 1 out of 2 boosts (not even server owner) so bot will remove all level roles once booster removes all boosts.

---

# Q. Bot missed boosters from server and only showing 1x boost on everyone.

It can be due to lack of proper setup OR possible downtime.

-   You can add missed booster by command `bb boosters add @user`
-   To further edit the number of boosts of users (1x or 2x) you need premium.

In case you added Booster Bot after someone booster 2 times, bot will take all existing booster's count as 1x as discord does not provide boost count per user to anyone.

**Note:** [Premium](https://boosterbot.xyz/premium) servers can add `+2` or `-1` like: `bb boosters add @user +2` to add 2 boost to someone.
