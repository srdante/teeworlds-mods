# Teeworlds Mods

This repository aims to have a complete listing of relevant content and mods from the Teeworlds Ecosystem. It contains scripts to build server binaries for multiple mods. For archived and binary mods, it also contains maps and assets that may be necessary for the mod to work.

## Summary

- [Supported Mods](#supported-mods)
    - [Maintained Mods](#maintained-mods)
    - [Archived Mods](#archived-mods)
    - [Binary Mods](#binary-mods)
- [Compiling Mods](#compiling-mods)
    - [Installing Dependencies](#installing-dependencies)
    - [Compiling For 0.6.x](#compiling-for-06x)
    - [Compiling For 0.7.x](#compiling-for-07x)

## Supported Mods

This is a list of mods that are currently supported by this repository. The mods are divided into three categories: Maintained Mods, Archived Mods, and Binary Mods.

### Maintained Mods

| Name | Website| Source | Forum Post | Version | Client |
|---------|---------|---------|---------|---------|---------|
| **DDNet** |  [Website](https://ddnet.tw/) | [Source](https://github.com/ddnet/ddnet) |  ------------------- | 0.6.x |
| **InfClass** | -------------------  | [Source](https://github.com/InfectionDust/teeworlds-infclassr) | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=12532) | 0.6.x |
| **MMOTee** |  ------------------- | [Source](https://github.com/kurosio/Teeworlds-Mmotee-Old) | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=12612) | 0.6.x |
| **ZombPanic** | ------------------- | [Source](https://github.com/miguilimzero/zombpanic) |  ------------------- | 0.6.x |

### Archived Mods

| Name | Website| Source | Forum Post | Version | Client |
|---------|---------|---------|---------|---------|---------|
| **Bomb Tag** | ------------------- | [Source](https://github.com/unique-clan/bomb) | ------------------- | 0.6.x |
| **Flagball** | ------------------- | [Source](https://github.com/miguilimzero/flagball) | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=12899) | 0.6.x |
| **Football** | ------------------- | [Source](https://github.com/unique-clan/football) | ------------------- | 0.6.x |
| **HMH-Monster** | ------------------- | [Source](https://github.com/miguilimzero/hmh-monster) | ------------------- | 0.6.x |
| **Hunter** | ------------------- | [Source](https://github.com/yangfl/teeworlds-hunter) | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=10408) | 0.6.x |
| **Killing Floor** | ------------------- | [Source](https://github.com/Siile/KillingFloor) | ------------------- | 0.6.x |
| **TeeSmash** | ------------------- | [Source](https://github.com/timazuki/TeeSmash) | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=11878) | 0.6.x |
| **TeeWare** | ------------------- | [Source](https://github.com/headshot2017/teeware-mod) | ------------------- | 0.6.x |
| **zCatch** | ------------------- | [Source](https://github.com/ddnet/zcatch) | ------------------- | 0.6.x |
| **CStrike** | ------------------- | [Source](https://github.com/ST-Chara/teeworlds-CStrike) | ------------------- | 0.7.x |
| **Streak** | ------------------- | [Source](https://github.com/miukmiuk/teeworlds_streak) | ------------------- | 0.6.x |
| **MMOTee** | ------------------- | [Source](https://github.com/MrCosmo666/Teeworlds-MRPG) | ------------------- | 0.7.x |[Custom Client](https://github.com/MrCosmo666/Teeworlds-MRPG) |
| **Nodes** | [Website](https://nodes.teeworlds.dev/) |[Source](https://github.com/teeworldsnetwork/nodes) | ------------------- | 0.7.x |[Custom Client](https://nodes.teeworlds.dev/downloads)|

* *Mandatory Client

### Binary Mods

For these mods, there are binaries that were published by their creators without the source. You can download them directly from this repository.

| Name | Website| Source | Forum Post | Version  | Client |
|---------|---------|---------|---------|---------|---------|
| **Battlefield** | ------------------- | ------------------- | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=9178) | 0.6.x | 
| **zChaos** | ------------------- | ------------------- | [Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=9682) | 0.6.x |  
| **LumLvl** | ------------------- | ------------------- |[Forum Post](https://www.teeworlds.com/forum/viewtopic.php?id=12849) | 0.7.x | 

## Installing Dependencies

First you must install the necessary dependencies on your system. You can run this script to install the necessary dependencies for compiling the mods.

> Scripts are made assuming you are running **Ubuntu 22.04** as operational system.

```sh
wget https://raw.githubusercontent.com/miguilimzero/teeworlds-mods/main/resources/default-dependencies.sh  -O - | sh
```

## Compiling For 0.6.x

Now you just need to execute the compile script for your desired mod:

```sh
wget https://raw.githubusercontent.com/miguilimzero/teeworlds-mods/main/0.6.x/MOD_FOLDER_NAME/compile.sh  -O - | sh
```

## Compiling For 0.7.x

Now you just need to execute the compile script for your desired mod:

```sh
wget https://raw.githubusercontent.com/miguilimzero/teeworlds-mods/main/0.7.x/MOD_FOLDER_NAME/compile.sh  -O - | sh
```
