## Stage Level-Streaming Suffixes

The following table presents an overview of the suffixes used in Tekken 7 and the types of assets associated with each streamed umap:

| Suffix Name  | Description                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| debug        | Includes debug information used by the developers.                                                                                       |
| demo         | Mostly used for story mode related changes, though it's used by every stage                                                              |
| edit         | The main UE4 editor map, it's essentially the main umap file that is used in the Unreal Editor to create the level.                      |
| effect       | Contains effect assets such as particle effects.                                                                                         |
| geom         | Main map/stage files that include the geometry/mesh data.                                                                                |
| light        | Represents the lighting information for the respective map/stage.                                                                        |
| lightstatic  | Usually includes baked lighting data and other light-related information.                                                                |
| mob          | Contains assets related to mobs, such as crowds or pedestrians.                                                                          |
| reload       | Contains assets that are intended to be reloaded when the battle restarts while the stage remains the same, such as destructible meshes. |
| sound        | Contains sound data associated with the respective stage.                                                                                |
| switch       | Used to switch between different stages within the game.                                                                                 |
| switch_debug | Includes debug information used by the developers related to stage switching.                                                            |
| WB           | Represents wall brush assets utilized within the game.                                                                                   |

**WARNING**: Different stages use different suffixes for level streaming. Used suffixes are documented in the Stage IDs table. Suffixes that aren't used by the stage won't be loaded.

## Stage IDs

The following is an overview of the stage IDs available in Tekken 7. These IDs are used to identify specific stages within the game.

| ID          | Name                                               | Used Level Streaming Suffixes                                                                                              | Playable         | Extra                                                          |
| ----------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------- | -------------------------------------------------------------- |
| stg00       | Mishima Dojo                                       | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg00sty    | Mishima Dojo (Story Version)                       | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Story Mode Only  |                                                                |
| stg01       | Forgotten Realm                                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg02       | Jungle Outpost                                     | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg03       | Arctic Snowfall                                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg04       | Twilight Conflict                                  | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg05       | Dragon's Nest                                      | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg06       | Souq                                               | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg06epi    | Story version of Souq                              | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Story Mode Only  |                                                                |
| stg07       | Devil's Pit                                        | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg08       | Mishima Building Elevator                          | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`<br>`switch`<br>`switch_debug` | Yes              |                                                                |
| stg08a      | Mishima Building Top                               | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg09       | Abandoned Temple                                   | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg10       | Duomo Di Sirio                                     | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg11       | Arena                                              | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg12       | G. Corp Helipad (Day)                              | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg12a      | G. Corp Helipad (Night)                            | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg12sty    | G. Corp Helipad (Story Version)                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Story Mode Only  |                                                                |
| stg13       | Undamaged Mishima Dojo                             | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Story Mode Only  | Heihachi versus Kazumi                                         |
| stg13sty    | Undamaged Mishima Dojo                             | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Story Mode Only  | Kazuya & Heihachi versus Jack-5s                               |
| stg14       | Brimstone and Fire                                 | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg15       | Precipice of Fate                                  | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg16       | Violet Systems                                     | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg16styLee | Violet Systems (Story Mode)                        | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Story Mode Only  | Lee versus Alisa                                               |
| stg17       | Deleted stage                                      | N\A                                                                                                                        | No               | Deleted stage, appears to be a playable version of stgChr_cust |
| stg18       | Violet Industries Hallway (Story Mode)             | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Story Mode Only  |                                                                |
| stg19       | Kinder Gym                                         | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg20       | Infinite Azure                                     | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg21       | Geometric Plane                                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg22       | Warm Up                                            | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg23       | Howard Estate                                      | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg24       | Hammerhead                                         | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Yes              |                                                                |
| stg26       | Jungle Outpost 2                                   | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg27       | Twilight Conflict 2                                | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg28       | Last Day on Earth                                  | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg29       | Infinite Azure 2                                   | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg30       | Cave of Enlightenment                              | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg31       | Vermilion Gates                                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes              |                                                                |
| stg32       | Island Paradise                                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`<br>`WB`                       | Yes              |                                                                |
| stg80       | Infinite Azure 2 (PlayStation 4 VR Stage)          | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Yes (PS4 VR)     | The files only exist in the PS4 version                        |
| stg81       | Infinite version of Devil's Pit                    | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | No               | The files only exist in the PS4 version                        |
| stg90       | Bowling Alley                                      | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`lightstatic`<br>`light`<br>`mob`<br>`reload`<br>`sound`              | Bowling Gamemode |                                                                |
| stgChr_cust | Customization Stage                                | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Customization    |                                                                |
| stgChr_view | The color changing part of the Customization stage | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | Customization    |                                                                |
| WallStage   | Developer test stage                               | `debug`<br>`demo`<br>`edit`<br>`effect`<br>`geom`<br>`light`<br>`mob`<br>`reload`<br>`sound`                               | No               |                                                                |