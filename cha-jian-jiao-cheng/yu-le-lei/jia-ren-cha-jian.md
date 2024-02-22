# 假人插件

使用需消耗2k金币，并且插件可能不太完善，无法修改名称，也无法删除。假人名字请谨慎\~

每位玩家上限3个假人

一个简单的例子以此类推

请自行测试，目前测试攻击没问题，满足基本功能\~

<mark style="color:red;">使用大型红石必须使用假人！大量的生物以及掉落物非常占用服务器带宽</mark>

Command (/doll create name)

/doll attack name interval 10

| 指令                                                                                         | 解释                                                            | 备注                                                                                                                  |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| attack \[action]                                                                           | Doll attacks(left click) towards it's line of sight           |                                                                                                                     |
| copy                                                                                       | Copy other Doll's action to Doll                              |                                                                                                                     |
| create \[skinName]                                                                         | Register Doll to server                                       | <p>skinName: Any authenticated player name<br>Default using creator's skin<br>Offline server uses default skins</p> |
| despawn                                                                                    | Offline Doll and save Data                                    |                                                                                                                     |
| drop \[stack/single] \[slots/action]                                                       | Drop Doll's Item from Slot                                    | <p>stack:Drop in maximum amount<br>Default:Drop 1 handheld item</p>                                                 |
| dismount                                                                                   | Let Doll gets off from current vehicle/entity                 |                                                                                                                     |
| echest                                                                                     | Open Doll's ender chest                                       |                                                                                                                     |
| exp \[all/level]                                                                           | Get Exp from Doll                                             | Default:1 level                                                                                                     |
| gset                                                                                       | Set Doll settings for All players                             | This will be overridden by pset                                                                                     |
| info                                                                                       | Show Doll data                                                | Not implemented                                                                                                     |
| inv                                                                                        | Open Doll's inventory                                         |                                                                                                                     |
| jump \[action]                                                                             | Make Doll jumps                                               |                                                                                                                     |
| <p>look &#x3C;yaw> &#x3C;pitch><br>look &#x3C;direction/player></p>                        | Copy Doll's head to target's orientation                      | \[yaw pitch]In +/-ve decimal                                                                                        |
| <p>lookat &#x3C;X> &#x3C;Y> &#x3C;Z><br>lookat &#x3C;player><br>lookat target [action]</p> | Set Doll's head pointing to player/coordinates/Entity         | \[X Y Z]In +/-ve decimal                                                                                            |
| menu                                                                                       | Open Doll's information panel                                 |                                                                                                                     |
| mount                                                                                      | Assign Doll to ride on nearby vehicle/entity                  |                                                                                                                     |
| move \[forwards/backwards]                                                                 | Assign Doll to move forward(W) or backward(S)                 |                                                                                                                     |
| pset                                                                                       | Set Doll settings for Specific player                         | This will override gset                                                                                             |
| remove                                                                                     | Remove Doll and its Data immediately                          | No recovery                                                                                                         |
| set                                                                                        | Open Doll settings                                            |                                                                                                                     |
| slot \[1-9]                                                                                | Set Doll's Handheld Slot                                      | Default:Slot 1                                                                                                      |
| sneak \[true/false]                                                                        | Toggle Doll to (un)sneak                                      | Default:Opposite from Current                                                                                       |
| spawn \[gridded]                                                                           | Spawn Doll at player position and copy player's pitch and yaw | gridded: Align at nearest line/quarter center                                                                       |
| sprint \[true/false]                                                                       | Toggle Doll to (un)sprint                                     | Default:Opposite from Current                                                                                       |
| stop \[all/movement]                                                                       | Stop Doll Action                                              | Default:All                                                                                                         |
| strafe \[left/right]                                                                       | Assign Doll to move left(A) or right(D)                       |                                                                                                                     |
| swap \[action]                                                                             | Swap item between Doll's main hand and off hand               |                                                                                                                     |
| tp \[gridded]                                                                              | Teleport Doll to player and copy player's pitch and yaw       | gridded: Align at nearest line/quarter center                                                                       |
| turn \<yaw> \<pitch>                                                                       | Rotate Doll's head by yaw(horizontal) and pitch(vertical)     | \[yaw pitch]In +/-ve decimal                                                                                        |
| use \[action]                                                                              | Doll uses/interacts(right click) towards it's line of sight   |                                                                                                                     |

\
