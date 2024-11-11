# Private role setup

!!! info

    These commands can be executed by Admins and Bot Manager only.

: The `bb prs` command allows you to set up private role perks for non-booster members. Members with an allowed role can use the [`bb role`](/commands/boosters/role) command to claim and set up their private roles in the same way as boosters.

## Allow roles

`bb prs allow @role`

: Members with this given role will be able to claim & maintain their private role.

## Remove roles

`bb prs remove @role`

: If any of the removed roles are taken from a user and they don't have any of the allowed roles, their private role will be deleted.

## Clear allow or remove roles

`bb prs <allow | remove> clear`

: You can clear the list of allowed as well as remove roles that can claim and remove private roles.

## Usage

: `bb prs <allow | remove> <role | clear>`
