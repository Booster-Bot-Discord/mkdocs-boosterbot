# Setup Commands

!!! info

    These commands can be executed by Admins and Bot Manager only.

: The `bb [setup | set]` command allows you to setup, edit, and remove bot settings.

## Prefix Setup Command

**Usage:** `bb setup prefix <new prefix>`

This command sets the prefix for the bot's commands.

**Examples**

| Command              | Explanation             |
| -------------------- | ----------------------- |
| `bb setup prefix !`  | Sets the prefix to `!`  |
| `bb setup prefix bb` | Sets the prefix to `bb` |

## Bot Manager

`bb setup manager <role>`

: This command sets the role that is able to edit bot settings, in addition to admins. To disable the bot manager role, use the `disable` argument.

## Additional Role

`bb setup add-role <role>`

: This command sets a role that the bot will automatically add to users when they boost the server. To disable the additional role, use the `disable` argument.

## Remove Role

`bb setup remove-role <role>`

: This command sets a role that the bot will automatically remove from users if they remove their boost from the server. To disable the remove role function, use the `disable` argument.

## Custom Role

`bb setup custom-role <number of boosts>`

: This command allows boosters to maintain their personal role if they have the required number of boosts.

## Gifts

`bb setup gifts <allowed gifts>-<required boosts>`

: This command allows boosters to gift their personal role to their friends if they are eligible.

## Auto Reactions

`bb setup ar <number of boosts>`

: This command allows boosters with the required number of boosts to set a custom emoji that the bot will react to any message that the booster is mentioned in.

## Base Role

`bb setup base-role <role>`

: This command sets the base role for the custom role. The bot will assign the custom role just above this role (make sure to enable the custom role first).

## Color

`bb setup color #2f3136`

: This command sets the color that the bot will use for all command embeds. Note that this will not change the color of greet embeds or log embeds.

## Log Events

`bb setup log-event <event> <channel>`

: This command sets the channel in which the bot will send log messages for the specified event. To disable log events, use the `disable` argument.

!!! info

    `bb setup log-channel <channel>`

    This command sets all log events to be sent to the same channel.

!!! info

    **If you want to remove any config**, type `disable` in value.
    Example : `bb setup gifts disable` will not allow anyone to gift their custom role.

## Usage

: `bb setup < prefix | manager | add-role | remove-role | custom-role | gift | base-role | color | log-event >`
