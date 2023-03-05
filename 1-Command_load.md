# Load Commands

Commands to preload necessary resources before starting the story.

## Load Character

- Syntax: `load spr {nameId} {sprName}`
- Example:

  ```txt
  load spr midori midori_spr
  ```

## Load Character in Communication State

- Syntax: `load sprC {nameId} {sprName}`
- Example:

  ```txt
  load sprC midoriC midori_spr
  ```

Student with communication status can be used with the `spr` command.

## Load (or Load in Communication State) | Custom Roles that can have Differentials

> Reference 1000x1200, scale 2.7

- Syntax: `load char/charC {nameId} {scale} {characterFolder} [imageList]`
- Example:

  ```txt
  load char/charC tt 2 test [01.png, 02.png, 03.png, 04.png]
  ```

Please distinguish characters by folders, such as:

- Character
  - Test
    - 01.png
    - 02.png
    - ...

## Load Background Scenery

- Syntax: `load bg {nameId} {bgName}`
- Example:

  ```txt
  load bg GameDevRoom_Night BG_GameDevRoom_Night.jpg
  ```

## Load Overlay Image

- Syntax: `load cover {nameId} {coverName}`
- Example:

  ```txt
  load cover Player popup02.png
  ```

## Load Background Music

- Syntax: `load bgm {nameId} {bgmName}`
- Example:

  ```txt
  load bgm Theme_64 Theme_64.ogg
  ```

## Load Sound Effect

- Syntax: `load se {nameId} {seName}`
- Example:

  ```txt
  load se Granted SE_Granted_01.wav
  ```

## End Pre-Load

A **must have** command after loading all the necessary resources. It's used to close preload functions.

- Syntax: `load end`
- Example:  

  ```cs
  load spr arona arona_spr
  load bgm theme_64 Theme_64.ogg
  load end
  ```
