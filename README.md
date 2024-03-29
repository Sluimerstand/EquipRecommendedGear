# EquipRecommendedGear
Adds a button to your character pane that equips the highest item level gear for your class & spec. Inspired by the same feature available in Final Fantasy XIV Online.

**Features**
- Adds a button. When you click the button, it does the thing;
- Instead of a button, you can also use: `/run EquipRecommendedGear.DoTheThing()`. Use argument `1` to only send a message if new gear is equipped, argument `0` for no messages, or no argument for all messages.

**Limitations**
- It will only consider soulbound items;
- It will only consider weapons suitable for your specialisation (2-handed weapons for Survival Hunter, daggers for Assassination Rogues, etc.);
- It will only consider weapons with your primary stat (Agility, Intellect, Strength) on them;
- It will not check rings or trinkets for your primary stat;
- It will not check the secondary stats of any gear;
- It will not use weights of any kind. It just looks at the item level. Number go up, happy brain chemicals.

**Known bugs**
- Using the button shortly after loading into the game will not always work properly. Try again a few seconds later.
