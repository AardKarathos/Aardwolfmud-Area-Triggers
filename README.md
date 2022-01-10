
# Aardwolfmud Area Triggers

This plugin allows one to define triggers that fire on entering/exiting an area/room.

Area Trigger Help
-----------------

**Syntax**: atrig import 

Opens a dialog where a json serialized configuration can be entered to replace the existing one.

**Syntax**: atrig export 

Outputs the json serialized configuration.

**Syntax**: atrig reload 

Reloads the plugin.

**Syntax**: atrig view [<*area id*>] 

Displays the triggers configured [for the given area].

**Syntax**: atrig clear <*area id*> [<*room num*>] 

Clears the triggers configured for the area [or specific room].

**Syntax**: atrig enter|exit <*area id*> [session] <*commands*>

Configures the enter|exit trigger for the area, optionally specifying whether it is only triggered once per session.

**Syntax**: atrig enter|exit <*area id*> <*room num*> [session|area] <*commands*>

Configures the enter|exit trigger for a room in the area, optionally specifying whether it is only triggered once per session, or once per entering the area.
