# Pls-help-me-whit-a-skript
So i have a skript named /grant and i want it to work like in a spesific world so like if im in kitpvp andd do /grant it only shows the kitpvp ranks command 


command /grant [<offline player>] [<text>]:
    permission: grant.rank
    permission message: §fUnknown command. Type "/help" for help
    trigger:
        if arg-1 is not set:
            send "&cPlease specify a player."
        else:
            open chest with 7 rows named "&cGrant&8: &3%arg-1%" to player
            wait 1 tick
            format slot 0 of player with book named "&4Owner" to run [make player execute command "systemgrant %arg-1% Owner"]

            format slot 1 of player with book named "&cCo-Owner" to run [make player execute command "systemgrant %arg-1% Co-Owner"]  

            format slot 2 of player with book named "&3Lead-Developer" to run [make player execute command "systemgrant %arg-1% Lead-Dev"]

            format slot 3 of player with book named "&3Dev" to run [make player execute command "systemgrant %arg-1% Dev"] 

            format slot 4 of player with book named "&dFriend" to run [make player execute command "systemgrant %arg-1% friend"] 

            format slot 5 of player with book named "&eAdmin" to run [make player execute command "systemgrant %arg-1% Admin"]

            format slot 6 of player with book named "&6Builder" to run [make player execute command "systemgrant %arg-1% builder"]

            format slot 7 of player with book named "&bMod" to run [make player execute command "systemgrant %arg-1% Mod"]

            format slot 8 of player with book named "&5Trial-Mod" to run [make player execute command "systemgrant %arg-1% Trial-Mod"] 

            format slot 9 of player with book named "&4You&ftuber" to run [make player execute command "systemgrant %arg-1% Youtuber"]

            format slot 10 of player with book named "&7Member" to run [make player execute command "systemgrant %arg-1% member"]
