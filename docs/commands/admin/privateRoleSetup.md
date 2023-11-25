# Private role setup

!!! info

    These commands can be executed by Admins and Bot Manager only.

: The `bb prs` command allows to setup private roles perks for non booster members. Members with allowed role can use [`bb role`](/commands/boosters/role) command to claim and setup their private roles same way as boosters.

## Allow roles

`bb prs allow @role`

: Members with this given role will be able to claim & maintain their private role.

## Remove roles

`bb prs remove @role`

: If any of remove roles are removed from user and they don't have any of the allowed roles, then their private role will be deleted.

## Clear allow or remove roles

`bb prs <allow | remove> clear`

: You can clear the list of allowed as well as remove roles that can claim and remove private roles.

## Usage

: `bb prs <allow | remove> <role | clear>`
