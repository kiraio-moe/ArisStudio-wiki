# Special Commands

## Comment

Make the current line as comment. This line will not be executed.

- Syntax: `//`
- Example:

  ```csharp
  // This is a comment
  ```

## Breakpoint

Command start with `===` will require user input by clicking/tapping screen to execute next command.

- Syntax: `===`
- Example:

  ```txt
  === This is a breakpoint
  ```

## Wait

Wait for the specified time in seconds before performing the mouse click.

- Syntax: `wait {seconds}`
- Example:

  ```csharp
  wait 2
  ```

## Mark Target

Mark current line. Often used together with `button` command.

- Syntax: `target {TargetName}`
- Example:

  ```csharp
  target choice_1
  ```

## Jump

Jump to marked line.

- Syntax: `jump {targetName}`
- Example:

  ```csharp
  jump choice_1
  ```

## Auto Interval

Set AUTO interval (automatically play dialogue) in seconds.

- Syntax: `auto {seconds}`
- Example:

  ```csharp
  auto 2.5
  ```

## Play Another Story

- Syntax: `ChangeTxt {storyName}`
- Example:

  ```csharp
  ChangeTxt Demo_EN
  ```
