# Age Role Commands

**Usage:** `bb agerole <add | remove | clear | claim> <duration> [role]`

The `bb agerole` command allows you to create booster level roles based on how long a user has been boosting the server.

## Subcommands

`bb agerole add 1w @role`: This command allows boosters to claim the `@role` role after boosting for 1 week.

`bb agerole remove 1w`: This command removes the age role for boosters who have been boosting for 1 week.

`bb agerole clear`: This command removes all age roles.

`bb agerole claim`: This command allows boosters to claim their age role.

## Duration Examples

- `1hour:20mins`
- `1week`
- `20d`

## Available Units

- `second` | `sec` | `s`
- `minute` | `min` | `m`
- `hour` | `hr` | `h`
- `day` | `d`
- `week` | `wk` | `w`
- `month` | `b`
- `year` | `yr` | `y`
