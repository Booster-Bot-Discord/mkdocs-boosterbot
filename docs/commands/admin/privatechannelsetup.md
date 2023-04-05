# Private channel setup commands

!!! info

    These commands can be executed by Admins and Bot Manager only.

: The `bb pcs` command allows to setup private channels perks for boosters.

## Select category for private channels

`bb pcs category`

: Set category of current message channel as category under which private channels will be created.

## Set allowed channel types

`bb pcs type <text | voice | both>`

: Boosters will be able to claim give type of channel (only 1 of available types).

## Lock role to disable view channel permission

`bb pcs lock @role`

: Bot will disable this role's VIEW_CHANNEL permission for each private channel.

## Allow role to enable view channel permission

`bb pcs allow @role`

: Bot will allow this role's VIEW_CHANNEL permission for new private channel. like allowing mod role to view all private channels.

## Allowed boosts to claim private channel

`bb pcs boosts <count>`

: Users with this many boosts can claim their private channels & invite people over.

## Set invite limit for private channels

`bb pcs invite <disable | boost-count> <invite-count>`

: Allow boosters to invite their allowed number of friends to their private channels.

## Usage

: `bb pcs <category | type | lock | boosts | invite | disable>`
