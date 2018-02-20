Sends 1 of 3 configured message(s) to a player when they place a tool cupboard.

Could be used as a reminder to remind people that they need to put resources in their cupboard to prevent their base from decaying.
## Permissions
You need to grant people the permission **cupboardmessages.use** in order for people to receive the message in-game. i.e 

- **cupboardmessage.use** -- Allows player to receive message
- **perm.grant group default cupboardmessages.use** -- Grant the default group the permission for all players

## Localization

Default language file (oxide/lang/en/CupboardMessages.json)
```json
{
  "Notice.1": "Remember to put resources in your cupboard to prevent it decaying!",
  "Notice.2": "This cupboard needs resources in its contents to prevent your base from being removed.",
  "Notice.3": "Your base will removed if you don't put sufficient resources in it's storage!"
}
```
