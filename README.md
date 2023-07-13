<h1 align="center">
  <br>
  <img src="https://imgur.com/PoNsDDc.png" alt="LiteFish logo" width="1024">
  <br>
</h1>

<h4 align="center">This is a premium plugin.</h4>

<p align="center">
    <a href="https://polymart.org/resource/litefish.4244">
        <img src="https://img.shields.io/badge/polymart-LiteFish-6bbeeb?style=for-the-badge"/>
    </a>
    <a href="https://discord.gg/p5F3f8pHFy" alt="Discord">
        <img src="https://img.shields.io/discord/1116979831113007146?label=discord&style=for-the-badge&color=6bbeeb"/>
    </a>
</p>

# Demo
Before buying, you can test this plugin on your server. To do this, visit the plugin's discord (https://discord.gg/PgDfrQx22f), there you will find a free version for testing with accompanying documentation
# About #
This plugin allows you to set custom loot for each biome. It also allows you to diversify fishing with a new mini-game.
# ShowCase: 
https://youtu.be/yZRGNApy8os
# New Fishing System

![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d59/b611f52800df/2023-06-10_04-47-02_1.gif?extra=CU9_gvJEhp_J6qwN2e1D2M3-MUu66ElKFlePSVXtfDppF7UH-1URu43IEm5Ueq261s6r_b093qTswC3kkJz5422b_Dip9rsP-tEuc5bFq3A8yZK95h8xJovZOurEJTp3cc0cagCV7n7J)
 
This system adds new mechanics
- the hook has health, this is how much it can miss the target. after losing all lives, the player does not catch anything
- each catch has its own parameters
·health - how many times do you need to hit the hook to catch the prey
·chance - what is the chance that this loot will drop
·experience - how much experience will be given with successful fishing
 
You can disable this mini-game in the config, leaving vanilla fishing, just setting custom loot for each biome category and its drop rate!
 
Also, at the end of fishing, there is a chance to move to the next level of rarity. A total of 5 rarity levels have been implemented. All parameters, including custom loot, drop chance and rarity increase chance are configured in the GUI.

# GUI
The GUI allows you to create categories where you can add a list of vanilla minecraft biomes to specify what loot will drop in these biomes
![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d34/a54c0abafbfc/2023-06-10_04-47-02_2.gif?extra=ik1u37dmgGNFtlAraP5MtB1Mv9TITRS7MsrABi5qfiDllbUccKPLPnyh0JtsaPc3zLnzEksSyrXuJU_L4C9hpoR6cQTIa5h4Gzs0g_aX7Frp3WJLL14nfrspZX9FaKZqB9VRcMVoBGRtzrguxV5gshS4)
  
You can add items directly from the inventory, adjust their drop rate, health and experience  
![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d31/1f53a1a26fcd/2023-06-10_04-47-02_3.gif?extra=c5K2I6dZ5LCQNoXKsUNfGKv4RyVD0tV8mSnTPMc1ZPLD7XPowNq9HoENTA9LywuGlrjOurWWVyoyXCVEbWSnkkaXQrjTCuZLzVL4vZvMHJNpM3ZQBVWL-PhqNHw3FnLDpXKbeydTmZdSs-y3UZ2HnCH4)
 
# BIG LOOT
Allows you to create a group of items that can appear in a box with a certain chance for each item  
![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d12/07e2ae6f874d/2023-06-10_04-47-02_4.gif?extra=EOrx02k0m_FvHF7w4kpRJFI98HNYv6SI3_FSUkog0m2ELQ0p-GU0b1knttQa9QnZ4fM5mjZYsdbfE63Hr87at8uk6AzRUD7NZ_Dnm99XMTjIEqopVTnAy15EjiRE99lyY4gGGHndpjdJRL3E31eZodn0)
 
# Monster
![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d46/415fb120a5ed/2023-06-10_04-47-02_5.gif?extra=sCTPU7Bim62kvFEbZqJW77WnrX-zPsZjM_pihiZ9DDOqV_fjoWR5Uv8S2VrUwm69WLKKgl8tl0fS1IAfMziManb9rsjI8oaWiKyeMBmD-3WDzYVNuhXGxffNB3s7DSa3ALme0mrh1gJODFFqXRByNXvZ)  
Allows you to set the chance at which a monster will eat prey in a given biome category

# Custom fish/weight

You can add custom random magnitude values ​​to rare drops.
![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2F15da25d1-8199-4e1a-915b-732acdcac9ca%2Fdefault%2Fattachment.png&v=2)
![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2Fa9a358d9-cf17-4880-8aaa-08ab4d172ba3%2Fdefault%2Fattachment.png&v=2)  
By default, values ​​are set from 0 to 5 kilograms. You can completely change both the range and the value type!
In the LiteFish.json config, you can find the measurement field and set the required value type and change the range that will be given by default in the defaultWeight field
![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2Ff0684e93-29b8-4c49-95e9-72a2e4f59f75%2Fdefault%2Fattachment.png&v=2)  
You can individually set the range for each drop. To do this, find it in the config (You can focus on the "material" and "chance" columns to find your item) and change the range in the "weight" field

![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2F3259d7e0-f6e4-4490-8e1f-0df182d954d7%2Fdefault%2Fattachment.png&v=2)  
![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2Ff5744c72-6609-4981-8f5c-ff019eed376d%2Fdefault%2Fattachment.png&v=2)  
Chances are increased at lower values. Accordingly, values ​​close to maxValue will be extremely rare.
Also if you click on the RMB frame (even being in someone else's private). Additional information about the caught fish will be displayed for 3 seconds

![alt text](https://images.polymart.org/proxy/?url=https%3A%2F%2Fpolymart-attachments.s3.amazonaws.com%2Fd4bde119-5c4b-4a93-94de-97b94482f01f%2Fdefault%2Fattachment.png&v=2)  
# Commands
/lfish reload - reload config LiteFish.json  
/lfish lang (language) - sets the language  
/lfish loot - main GUI  
/lfish print - displays a drop map for the current biome in chat  

# PlaceholderAPI
In the LiteFish.json file, you can set a dynamic chance based on data from various plugins using the PlaceholderAPI.

"expressions": {  
    "chanceRare": "10 + 15 * (%ecoskills_fishing% / 50)",  
    "chanceEpic": "10 + 10 * (%ecoskills_fishing% / 50)",  
    "chanceLegendary": "10 + 10 * (%ecoskills_fishing% / 50)",  
    "chanceImmortal": "10 - 5 * (%ecoskills_fishing% / 50)"  
  }  
"chanceMonster": "50 - 25 * (%ecoskills_fishing% / 50)"  
(lvl0=50%, lvl50=0%)  

# Catch entity
The plugin allows you to enable catch of any entity, along with NBT data
![alt text](https://psv4.userapi.com/c909618/u794072425/docs/d46/c11804bdd66b/2023-06-10_04-47-02_6.gif?extra=i8xPUE1tY5d0YwJL1RDN7mlL34P7lEiZl8NsQR95Mqx3CmwKYK6fjpndt6aVAkVsdxRJgYxwPyOtfyFAG2Z7kDIvB1dkbPM82ryHbOknfmDYWeN8_v9X0vFM7cCMq7Kt8xiOa4yEIYKIjH37dFr184In)

Enable in config "dropEntityFromEgg": true  
Give yourself a summon egg with the right NBT tags and just move it to the GUI  
/give @p cat_spawn_egg{HandDropChances:[2F,2F],HandItems:[{id:"minecraft:diamond",Count:64},{}]}}  
You can disable this feature if you want the eggs to drop as an item.

# Config
You can:  
-сhange the base cursor movement speed and its acceleration depending on the increase in the rarity of the loot  
-сhangethe base hook health  
-сhange customTitle and customSubTitle. This message will appear when certain loot drops like minecraft Title  
-set the color palette for the mini-game interface of each biome category. Supports HEX color  
  
# Future Additions
Fish boss fight :-)

# Language
If you would like to make your own translation, you can upload it to https://github.com/NekoMaidTop4ik/LiteFish

# Buy
https://polymart.org/resource/litefish.4244
