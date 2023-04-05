# Emoji Commands

!!! info

    These commands can be executed by Admins and Bot Manager only.

The `bb emoji` command allows you to restrict certain emojis to specified roles. This means that only members with the specified role will be able to use the restricted emoji.

## Lock Emoji to Role

**Usage:** `bb emoji lock <emoji> @role`: This command restricts the specified emoji to the given role.

**Examples**

| Command                          | Explanation                                        |
| -------------------------------- | -------------------------------------------------- |
| `bb emoji lock 😂 @Member`       | Restricts the 😂 emoji to the `@Member` role       |
| `bb emoji lock 🎉 @Celebrations` | Restricts the 🎉 emoji to the `@Celebrations` role |

## Lock Normal Emojis to Role

`bb emoji lock normal @role`

: This command will restrict all normal (non-animated) emojis to the given role.

## View Emoji Restrictions

`bb emoji info`

: This command will show all current emoji restrictions and which roles can access which emojis.

## Reset Emoji Restrictions

`bb emoji reset`

: This command will reset all emoji restrictions, allowing everyone to use every emoji.

## Usage

: `bb emoji <lock | unlock | info | reset> <emoji | normal | animated> <role>`
