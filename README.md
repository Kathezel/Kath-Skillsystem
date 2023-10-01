# Kath-Skillsystem
A Minecraft skillsystem Datapack

# What does it do?
This Datapack implements a simple and not too overpowered skillsystem which is using your EXP to convert it into skillpoints which you then can use to skill **into 10 different Skills.**

**Combinable datpack: https://modrinth.com/datapack/kaths-simple-bossmobs**

<details>
<summary>Details</summary>

- Every skill needs 10 skillpoints to max out.
    - HP-Regen only has 2level but cost 10 skillpoints to max.
- The amount of EXP needed increases by 100 EXP every skillpoint.
    - Max EXP use is 2000EXP ~35lvl per skillpoint.
- You will lose all skillpoints and skills after you die.
    - Eat a enchanted golden apple to save your skills
    - *or* use the command provided in the *usefull commnds* tab

</details>

<details>
<summary>Skills you can level up</summary>

- Armor
- Armor toughness
- Attack speed
- Damage
- HP
- HP-Regen
- Knockback resistance
- Luck ( Fishing luck, **not Fortune or Looting**  )
- Movement speed

**in Planing:**
- Pickup range


</details>

<details>
<summary>Useful Commands:</summary>

- Get all datapack Items:
    - /function k_skills:give_items
---
- Get only the skillbook:
    - /function k_skills:items/give_skillbook
---
- Deactivated death penalty:
    - /scoreboard players set test no-death-pen 1
---
- Activated death penalty: **default** 
    - /scoreboard players set test no-death-pen 0
---
- Uninstall the datapack and delete all scoreboards and written data:
    - /function k_skills:uninstall


</details>



# This datapack is dependent on my resource pack!
Without the resource pack you will not see the right icons for the new items, you will only see a carrot-on-a-stick.

# What does it add?
It adds 3 new items
- Skillbook = Which let you use the skillsystem
- Skill reset = With this item you can reset your skill and regain and re-assign any used points
- Potion of Revoke = Can be used 10 times and gives you your EXP back as long you have an unused skillpoint.

A skilltree with 9 skills which you can skill freely and up to 10 times each skill.

New Advancements with infos about the datapack and 5 new goals

# How to start.
You need to get the skillbook first by crafting it.

<details>
<summary>Crafting Recipes:</summary>

![Skillbook Recipe](https://cdn.modrinth.com/data/B8bh5HHu/images/9ca265236a4b4beb0abac391b52104be49827f68.png)

![Skill reset Recipe](https://cdn.modrinth.com/data/B8bh5HHu/images/a412e8c5169c5dcd046cd1d4f53ec9fa23929204.png)

![Potion of Revoke Recipe](https://cdn.modrinth.com/data/B8bh5HHu/images/a43477e6ea72e5bfe2cd6b6b20e98a56fee7bb5f.png)

</details>

After you got the skillbook rightclick it and you will get a messages in chat which you can interact with.
Every skill show you how far you can skill and how much it costs. 

<details>
<summary>MSG after rightclicking the Skillbook:</summary>

![MSG after clicking the Skillbook](https://cdn.modrinth.com/data/B8bh5HHu/images/2313f9edd49751b00f64d6322295c42cd1e135fd.png)

Click on the **[+]** to level a Skill
</details>

First you need to get a skillpoint. 
On the right you see a scoreboard of your skill, there you see, how much EXP and which level you need to be to get the next skillpoint. Click on "Add Skillpoint" to convert you EXP to skillpoints.
`this uses your EXP not level but you still need to be at least the shown level to add a point`

<details>
<summary>Players skills shown by holding the skillbook:</summary>

![Player Skills shown by holding the Skillbook](https://cdn.modrinth.com/data/B8bh5HHu/images/7af0767a20da9870e3c62d690d19cc1d0807aad0.png)

</details>

# Multiplayer
This datapack had multiplayer in mind from the beginning so it can also be used on servers. There is only one known issue in multiplayer, explained below, but it's not gamebraking.

For multiplayer only the server world needs to have this datapack active.


# Know issues:
- In multiplayer if two players are holding the skillbook at the same time, the display for the skills will not work correctly.

# Other Stuff I did:
https://modrinth.com/user/Kathezel

**- Kaths Simple Bossmobs: https://modrinth.com/datapack/kaths-simple-bossmobs**

**- Kaths Music Everywhere: https://modrinth.com/resourcepack/kahts-all-the-music**

**- Kaths Teleporter : https://modrinth.com/datapack/kaths-teleporter**
