## Role Assign

!rstart *message ID*

This starts a role assign creation session and allows you to configurate a message to become a role assign. Allows the usage of other commands.

!rrole add *Emote*-*Role Name*

This adds a reaction to the selected message with the emote that, when reacted with, assigns the given role.

!rnick add *Emote*-*Role Name*

This adds a reaction to the selected message with the emote that, when reacted with, assigns the given name tags.

!rrole remove *Emote*-*Role Name*

Removes the reaction on the selected message and disables the role assign for that reaction. Only works in an !redit session.

!rnick remove *Emote*-*Role Name*

Removes the reaction on the selected message and disables the role assign for that reaction. Only works in an !redit session.

!redit *message ID*

This starts a role assign edit session and allows you to change the configuration for a message. Allows the usage of other commands.

!rfinish

This ends and saves the role assign session. Role assigns will not work till they are saved

## Embed Creation

!ecreate *Channel mention*

Starts an embed creation session and allows the usage of other commands

!etitle *Title*

Adds the title to the embed, only avalible during an embed creation session.

!etext *Text*

Adds the text to the embed, only avalible during an embed creation session.

!efinish

Ends the embed creation session and sends the embed to the desired channel.

## Streamer Module

!streamermodule enable/disable

Enables or disables the streamermodule. Is disabled by default.

!streamermodule role *Role Name*

Specifies the role that should be assigned when someone is streaming. Is "Streaming" by default.

!streamermodule restrict *Role Name*

Specifes the role that members must have when getting the streamer role. Put "@everyone" to not have a required role, is "@everyone" by default.

## Invite Buster
