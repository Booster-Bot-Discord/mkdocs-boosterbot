# Stats Commands

!!! info
    
    These commands can be executed by Admins and Bot Manager only.


The `bb stats` command allows you to create or update voice channels (VCs) for server booster stats.

## Available Sub Commands

`bb stats create <stat option>`
:   Create a new VC for the specified stat option

`bb stats link <stat option> #VC`
:   Use the specified VC for the specified stat option

`bb stats update <stat option> <new name>`
:   Set the name of the VC for the specified stat option to the specified new name

`bb stats delete <stat option>`
:   Delete the VC for the specified stat option

## Available Stat Options

- `allboosts`: all-time total boosts on the server

- `currboosts`: current boosts on the server

- `allboosters`: current number of boosters on the server

- `currboosters`: number of all-time server boosters

## Usage

`bb stats <link | create | update | delete> <stat option>`
