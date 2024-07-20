# CustomDrills


Easy to use

Config:

```yaml
Drills:
  ExampleDrill:
    DisplayName: "Example Drill"
    Item: "DIAMOND_PICKAXE"
    Radius: "2x2x2x" # 2 UP 2 LEFT 2 RIGHT 2 DOWN
    Lores:
      - This is a example drill !
    DisabledWorlds:
      - spawn
      - pvp
    Enchantments:
      - MENDING / 1 # First your Enchantment then the Level of the Enchant
    Permission: "z.drill.use.%drillName%" #DONT CHANGE THIS !!!!!!!!!!!!!!!!!!!!
    NeedPerms: true # Typ true if you want that only Players with the Permission can use this drill
    DrillItemID: 1 #You need to enter this so that the Drill Item has a Special Item and can not get be duped or renamed with a amboss
    BlackListedItems:
      - BEDROCK
      - OBSIDIAN
    ConnectedBlockBreak: # The Radius will be ignored if this is enabled
      Enabled: true
      BlockTypes:
        - OAK_LOG
        - SPRUCE_LOG
        - BIRCH_LOG
        - JUNGLE_LOG
        - ACACIA_LOG
        - DARK_OAK_LOG

          #You can create new Drills with Copying the Text above me and paste it and change the The Name of the Drill and the ID


ADrills:
  Messages:
    CantMine: "#FF0000You cant mine here!"
    NotFound: "#FF0000Drill not Found"
    PlayerNotFound: "#FF0000Player not Found"
    InvFull: "#FF0000Please clean up your Inventory"
    Received: "&7You got #2F6EFB%amount% &7%drillName%'s"
    NumberErr: "#FF0000Amount must be a Number!"
    NoPerm: "#FF0000You dont have the required Permission to use this Drill"
```
