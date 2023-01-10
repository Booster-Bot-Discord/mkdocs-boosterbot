# Greet Configuration Commands

!!! info
    
    These commands can be executed by Admins and Bot Manager only.

The following commands are used to setup, edit, and remove greet configurations for your Discord server.

## Greet Channel

`bb greet channel <channel | disable>`

:   This command sets the channel in which the bot will send a random greet message from a list of custom messages. To disable the greet channel, use the `disable` argument.

## Greet Message

`bb greet message <message | disable>`

:   This command adds a message to the list of greet messages that the bot can send. Non-premium users can add up to 3 messages. To clear all greet messages, use the `disable` argument. Note that you cannot edit or remove individual messages without clearing the entire list and re-adding them.

## Add-on Message

`bb greet addon <message | disable>`

:   This command sets a plain message that the bot will send along with or outside of an embed (if enabled) to ping a role or user. To disable the add-on message, use the `disable` argument.

## Image

`bb greet image <image_url | disable>`

:   This command adds an image URL to the list of greet images that the bot can send. Non-premium users can add up to 2 images. To clear all greet images, use the `disable` argument. Note that you cannot edit or remove individual images without clearing the entire list and re-adding them.

## Emoji

`bb greet emoji <emoji | disable>`

:   This command sets an emoji that the bot will use for an automatic reaction on the default boost message. To disable the emoji, use the `disable` argument.

## React

`bb greet react <msg>`

:   This command sets which message the bot will use the emoji reaction on. The options are:

    - `default`: the default system message (default)
    - `custom`: the bot's custom greet message (if enabled)
    - `both`: both messages

## DM

`bb greet dm <enable | disable>`

:   This command enables or disables the bot sending the greet message in the Direct Message (DM) of the server booster.

## Booster Stats

`bb greet stats <enable | disable>`

:   This command enables or disables the bot sending booster stats, such as the total number of boosts and the server boost level, in the greet message. This is enabled by default.

## Test

`bb greet test`

:   This command sends a test greet message as configured.

## Embed

`bb greet embed <enable | disable>`

:   This command enables or disables the bot sending the greet message in an embed. This is enabled by default.

## Usage

:   `bb greet < channel | message | addon | author | author-icon | title | footer | footer-icon | image | dm | emoji | react | embed | thumbnail | stats | test >`
