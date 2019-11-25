[![PRs welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg)](https://github.com/xLeDocteurx/vue-avataaars/pulls)
[![Gitter](https://img.shields.io/gitter/room/cvue-avataaars/community)](https://gitter.im/vue-avataaars/community)
[![GitHub](https://img.shields.io/github/license/xLeDocteurx/vue-avataaars)](https://github.com/xLeDocteurx/vue-avataaars/pulls)

# Vue js component for Avataaars
(Work in progress)

This is a port from  Sketch library [Avataaars](https://avataaars.com/) designed by [Pablo Stanley](https://twitter.com/pablostanley). 

<p align="center"><img src='avataaars-example.png?raw=true' style='width: 300px; height: 300px;' /></p>

## Features

 - SVG based
 - Light weight 
 - Scalable
 - Easy to use
 - Easy to integrate with custom editor
 - Comes from [Avataaars](https://avataaars.com/)

#### Roadmap to 0.0.1 and NPM
- Basic Avataaars component with all the svg assets.

#### Roadmap to 0.1.0
- Feed the Avataaars component with a hash to procedurally generate an avatar.

#### Roadmap to 0.2.0
- Fully customizable Avataaars editor.

#### Roadmap to success
- Providing an open API like lorempicsum or gravatar.

#### How it works

Import the Avataaars component. Pass it an object called "avatarOptions" with some parameters. Let the magic happen.

## Installation
```

```

## Usage

- Using the Avataaars component only :
```vue
 <template>
  <Avataaars :avatarOptions="{
    backgroundType: selectedBackgroundType,
    backgroundColor: selectedBackgroundColor,
    skinColor: selectedSkinColor,
    clothesType: selectedClothesType,
    clothesColor: selectedClothesColor,
    clothesGraphicsType: selectedClothesGraphicType,
    mouthType: selectedMouthType,
    facialHairType: selectedFacialHairType,
    facialHairColor: selectedFacialHairColor,
    accessoriesType: selectedAccessoriesType,
    topType: selectedTopType,
    topColor: selectedTopColor,
  }" />
</template>

<script>
import Avataaars from '../Avataaars'

export default {
  name: 'Your component',
  components: {
    Avataaars,
  },
</script>
```

- Using the Avataaars editor in addition to the Avataaars component :
```vue

```

## Props for avatarOptions
```
{
    "backgroundType": ["circle", "transparent"],
    "backgroundColor": ["black", "blue01", "blue02", "blue03", "gray01", "gray02", "heather", "pastelBlue", "pastelGreen", "pastelOrange", "pastelRed", "pastelYellow", "pink", "red", "white"],

    "skinColor": ["tanned", "yellow", "pale", "light", "brown", "darkBrown", "dark"],

    "clothesType": ["blazerShirt", "blazerSweater", "collarSweater", "graphicShirt", "hoodie", "overall", "shirtCrewNeck", "shirtScoopNeck", "shirtVNeck"],
    "clothesColor": ["black", "blue01", "blue02", "blue03", "gray01", "gray02", "heather", "pastelBlue", "pastelGreen", "pastelOrange", "pastelRed", "pastelYellow", "pink", "red", "white"],
    "clothesGraphicsType": ["none", "bat", "cumbia", "deer", "diamond", "hola", "pizza", "resist", "selena", "bear", "skullOutline", "skull"],
    
    "eyebrowType": ["angry", "angryNatural", "default", "defaultNatural", "flatNatural", "raisedExcited", "raisedExcitedNatural", "sadConcerned", "sadConcernedNatural", "unibrowNatural", "updown", "updownNatural"],
    "eyesType": ["close", "cry", "default", "dizzy", "eyeroll", "happy", "hearts", "side", "squint", "surprised", "wink", "winkWacky"],
    "mouthType": ["concerned", "default", "disbelief", "eating", "grimace", "sad", "screamOpen", "serious", "smile", "tongue", "twinkle", "vomit"],
    
    "facialHairType": ["blank", "beardMedium", "beardLight", "beardMajestic", "moustacheFancy", "moustacheMagnum"],
    "facialHairColor": ["auburn", "black", "blonde", "blondeGolden", "brown", "brownDark", "platinum", "red"],

    "accessoriesType": ["blank", "kurt", "prescription01", "prescription02", "round", "sunglasses", "wayfarers"],
    "topType": ["none", "eyepatch", "hat", "hijab", "turban", "winterHat1", "winterHat2", "winterHat3", "winterHat4", "longHairBigHair", "longHairBob", "longHairBun", "longHairCurly", "longHairCurvy", "longHairDreads", "longHairFrida", "longHairFro", "longHairFroBand", "longHairNotTooLong", "longHairShavedSides", "longHairMiaWallace", "longHairStraight", "longHairStraight2", "longHairStraightStrand", "shortHairDreads01", "shortHairDreads02", "shortHairFrizzle", "shortHairShaggyMullet", "shortHairShortCurly", "shortHairShortFlat", "shortHairShortRound", "shortHairShortWaved", "shortHairSides", "shortHairTheCaesar", "shortHairTheCaesarSidePart"],
    "topColor": ["auburn", "black", "blonde", "blondeGolden", "brown", "brownDark", "platinum", "red"]
}
```
