#FETCH QUEST! Front End Repo
Back end repo: https://github.com/Brandv/fetch-quest
*************
###Description:
Fetch Quest! is gamified errand app that turns mundane errands into fantastical quests! Quests are completed by visiting the location of the errand. Upon completion, the user is rewarded with loot which can be used to customize their avatar.

###Key Technologies:
- Angular 2
- Ionic 2
- Google Maps API
- Google Places API

API Key:

d67cd72d34986c1d7d8a42cfb7513f07

### Team Members:
Rich Richardson
Vadim Brand
Robert Gervais
Dereck Miller

Team norms:
- A deep ~~dislike~~ ~~begrudging~~ respect of Travis CI builds

Quest format:
******
  example:
 [
  {
hook: "A dire turtle's on the loose!",
description: "The turtle's on a crazy rampage, causin' all sorts of nonsense. Subdue and capture",
icon_url: "http://i.imgur.com/Vow5Cv0.png" _must be maximum 40px by 40px_
  },
#add more here!
  {
hook:
description:
icon_url:
 }
]



Item format:
******
 [
  {
slot: , _head, bracers, pants_
rarity: , _0-3 won't say which one's the high number_
image_url: ,_must be maximum 40px by 40px_
description: ,
name:
  },
  {
slot: ,
rarity: ,
image_url: ,
description: ,
name:
  }
]


Npc format:
******
 [
  {
  avatar_url: ,
  name:
  },
  {
  avatar_url: ,
  name:
  }
 ]
