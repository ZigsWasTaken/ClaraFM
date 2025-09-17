# Clara Triggers Table.
## This is simply a place to hold all Triggers cleanly.

<br>
<br>

### See Format Below.

<br>
<br>

## Format:
## {
## RESOURCE: 
## TRIGGER: 
## WHATDO: 
## DATEFOUND: 
## }
<br>
<br>
<br>
<br>
Client Triggers:
{
RESOURCE: cv-ui
TRIGGER: TriggerEvent('cv-ui:Toast', msg[string], color[string - Red,Blue,Green], "build", 0, "toast")
WHATDO: Shows ui popup with custom text
DATEFOUND: 9/11/25
}
<br>
<br>
<br>
<br>
<br>
Server Triggers:
{
RESOURCE: brutal_pets
TRIGGER: TriggerServerEvent('brutal_pets:server:AddItems', {{"WEAPON_BALL", 1}})
WHATDO: Gives WEAPON_BALL, Server has check for other items so can only give ball. Maybe you can sell them somewhere?
DATEFOUND: 9/14/25
}
