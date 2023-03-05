# Button Commands

Create buttons to interact with.

## One Button

- Syntax: `button {buttonContent} {markedTargetName}`
- Example:

  ```txt
  button 'This is a button' tB
  ```

## Two Buttons

- Syntax: `button {buttonContent1} {markedTargetName1} {buttonContent2} {markedTargetName2}`
- Example:

  ```txt
  button 'Got it!' tB Should? tB
  ```

## Three Buttons

- Syntax: `button {buttonContent1} {markedTargetName1} {buttonContent2} {markedTargetName2} {buttonContent3} {markedTargetName3}`
- Example:

  ```txt
  button 'First button' tB1 'Second button' tB2 'Third button' tB3
  ```

## Auto Select Button (Not clicked automatically)

You can have up to 3 buttons like before.

- Syntax: `buttonS {selectedButtonNumber} {buttonContent} {markedTargetName}`
- Example:

  ```txt
  buttonS 2 'Play Tutorial' tN 'Directly preview the existing emoticon animation' tEmo
  ```
