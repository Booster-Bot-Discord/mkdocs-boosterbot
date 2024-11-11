# Private channel setup

!!! info

    These commands can be executed by Admins and Bot Manager only.

: The `bb pcs` command allows you to set up private channel perks for boosters.

## Select category

`bb pcs category`

: Set the category of the current message channel as the category under which private channels will be created.

## Allow channel types

`bb type <text | voice | both>`

: Boosters will be able to claim a type of channel (only 1 channel is allowed for available types).

## Hide private channels

`bb pcs lock @role`

: The bot will disable this role's VIEW_CHANNEL permission for each private channel.

## Allow access to private channels

`bb pcs allow @role`

: The bot will allow this role's VIEW_CHANNEL permission for new private channels. For example, if you want server managers to access all private channels (ADMINS will by default have permission to all private channels).

## Boosts required to claim a private channel

`bb pcs boosts <count>`

: Users with this many boosts can claim their private channels & invite people over.

## Allow boosters to invite friends to private channels

`bb pcs invite <disable | boost-count> <invite-count>`

: Allow boosters to invite their allowed number of friends to their private channels.

## Usage

: `bb pcs <category | type | lock | boosts | invite | disable>`
