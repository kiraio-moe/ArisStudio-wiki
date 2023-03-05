# Character Commands

{nameId} is obtained when you preload a character. See: [Load Command: Load Character](./1-Command_load.md#load-character "Load Command: Load Character") | [Load Command: Load Character in Communication State](./1-Command_load.md#load-character-in-communication-state "Load Command: Load Character in Communication State")

## Show Character

- Syntax: `{nameId} show`

## Hide Character

- Syntax: `{nameId} hide`

## Show Character (Immediately)

- Syntax: `{nameId} showD`

## Hide Character (Immediately)

- Syntax: `{nameId} hideD`

## Highlight Character

0 is dark, 1 is bright. 0.5 and 1 are recommended.

- Syntax: `{nameId} hl/highlight {0.0~1.0}`

## Set Character Facial State

~~How to use [State Preview in Web Browser](./Draft_State_Preview_Web_Browser.md).~~

- Syntax: `{nameId} state {stateId}`
- Example:

  ```txt
  hifumi state 03
  ```

## Set Character Emoticon Expressions

See [available emoticon list](./Character_Emoticon_List.md "Available Emoticon List").

- Syntax: `{nameId} emo/emoticon {emoName}`
- Example:

  ```txt
  hifumi emo Action
  ```

## Play Character Animation

### Up

- Syntax: `{nameId} up`

### Down

- Syntax: `{nameId} down`

### Reset

Set an empty animation to restore the animation state.

- Syntax: `{nameId} empty`

## Set Character Position

### Set X Axis Position

Recommended value are: -10, -5, 0, 5, 10.

- Syntax: `{nameId} x {position}`

### Move to a X Axis Position at Custom Speed

- Syntax: `{nameId} moveX/move {position} {speed}`

### Set Y Axis Position

- Syntax: `{nameId} y {position}`

### Move to a Y Axis Position at Custom Speed

- Syntax: `{nameId} moveY {position} {speed}`

### Close Up Character

Bring the character closer to the camera.

- Syntax: `{nameId} close`

### Bring to Back Character

Move the character away from the camera.

- Syntax: `{nameId} back`

### Shake Character

Shake the character's X/Y axis.

- Syntax: `{nameId} shakeX/shakeY {speed} {amplitude} {duration}`

### Change Character Layer Order

The default character layer order is 0.

- Syntax: `{nameId} z {z-index}`

## Old Spr Commands

<details>
<summary>CLICK TO VIEW</summary>

### Show Character (Spr)

- Syntax: `spr show {nameId}`

### Hide Character (Spr)

- Syntax: `spr hide {nameId}`

### Show Character (Immediately) (Spr)

- Syntax: `spr showD {nameId}`

### Hide Character (Immediately) (Spr)

- Syntax: `spr hideD {nameId}`

### Highlight Character (Spr)

0 is dark, 1 is bright. 0.5 and 1 are recommended.

- Syntax: `spr hl/highlight {nameId} {0.0~1.0}`

### Set Character Facial State (Spr)

~~How to use [State Preview in Web Browser](./Draft_State_Preview_Web_Browser.md).~~

- Syntax: `spr state {nameId} {stateId}`
- Example:

  ```txt
  spr state hifumi 03
  ```

### Set Character Emoticon Expressions (Spr)

See [available emoticon list](./Character_Emoticon_List.md "Available Emoticon List").

- Syntax: `spr emo/emoticon {nameId} {emoName}`
- Example:

  ```txt
  spr emo hifumi Action
  ```

### Set Character Animation (Spr)

#### Up (Spr)

- Syntax: `spr up {nameId}`

#### Down (Spr)

- Syntax: `spr down {nameId}`

#### Reset (Spr)

Set an empty animation to restore the animation state.

- Syntax: `spr empty {nameID}`

### Set Character Position (Spr)

#### Set X Axis Position (Spr)

Recommended value: -10, -5, 0, 5, 10.

- Syntax: `spr x {nameID} {x}`

#### Move to a X Axis Position at Custom Speed (Spr)

- Syntax: `spr moveX/move {nameID} {x} {speed}`

### Set Y Axis Position (Spr)

- Syntax: `spr y {nameID} {y}`

#### Move to a Y Axis Position at Custom Speed (Spr)

- Syntax: `spr moveY {nameID} {y} {speed}`

#### Close Up Character (Spr)

Bring the character closer to the camera.

- Syntax: `spr close {nameID}`

#### Bring to Back Character (Spr)

Move the character away from the camera.

- Syntax: `spr back {nameId}`

#### Shake Character (Spr)

Shake the character's X/Y axis.

- Syntax: `spr shakeX/shakeY {nameId} {speed} {amplitude} {duration}`

#### Change Character Layer Order (Spr)

The default character layer order is 0.

- Syntax: `spr z {nameID} {z-index}`

</details>
