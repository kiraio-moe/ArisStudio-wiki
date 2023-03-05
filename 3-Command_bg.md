# Background Commands

> Reference image size 1280x900

## Set Background Image

{nameId} is obtained when you preload a background. See: [Load Command: Load Background Scenery](./1-Command_load.md#load-background-scenery "Load Command: Load Background Scenery")

- Syntax: `bg set {nameId}`
- Example:

  ```txt
  bg set ClassRoom2
  ```

## Show Background (Gradually)

- Syntax: `bg show`

## Hide Background (Gradually)

- Syntax: `bg hide`

## Show Background (Immediately)

- Syntax: `bg showD`

## Hide Background (Immediately)

- Syntax: `bg hideD`

## Shake Background

- Syntax: `bg shakeX/shakeY {shakeSpeed} {shakeAmplitude} {shakeDuration}`
- Example:

  ```txt
  bg shakeY 10 -40 1
  ```
