# Q. How to setup Booster Bot?

Booster Bot needs basically only 1 thing: System channel enabled and "Send message when someone boosts this server" enabled in your server settings.

Make sure the bot has read & send message permissions along with embed links, so that the bot can send beautiful Greet Messages when someone boosts and track them for you.

Refer to this [YouTube video](https://youtu.be/FdyeBrE7VHo) for basic bot setup.

**OR** checkout docs for [#getting started](/setup) command.

---

# Q. Is there any way to give special role to double-boosters?

Yes, Booster Bot tracks each boost and keeps count of boosts for each member, and you can use `bb lvl-role` to set up boost level roles. Check `bb help lvl-role` to know more about level roles OR refer to the [#level role docs](/commands/boosters/lvlrole/).

However, no one can detect if someone removed 1 out of 2 boosts (not even the server owner), so the bot will remove all level roles once a booster removes all boosts.

---

# Q. Bot missed boosters from the server and is only showing 1x boost on everyone.

It can be due to a lack of proper setup OR possible downtime.

-   You can add missed boosters by the command `bb boosters add @user`
-   To further edit the number of boosts of users (1x or 2x) you need premium.

In case you added Booster Bot after someone boosted 2 times, the bot will take all existing boosters' count as 1x, as Discord does not provide boost count per user to anyone.

**Note:** [Premium](https://boosterbot.xyz/premium) servers can add `+2` or `-1` like: `bb boosters add @user +2` to add 2 boosts to someone.
