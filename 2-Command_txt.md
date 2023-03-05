# Dialogue Commands

## Set Dialogue

`t` can also be replaced by `txt`.

- Syntax: `t {studenName} {studentCommunityName} {conversationContent}`
- Example:

  ```txt
  t Hifumi 'Remedial Department' 'Huh...? Sensei, don'\t you know the wave cat?'
  ```

## Set Dialogue (With highlight)

The specified character will be highlighted and other characters will be dimmed.

- Syntax: `th {nameId} {studentName} {studentCommunityName} {conversationContent}`
- Example:

  ```txt
  th hifumi Hifumi 'Remedial Department' 'Huh...? Sensei, don'\t you know the wave cat?'
  ```

## Hide Dialogue Panel

- Syntax: `text hide`
- Example:

  ```txt
  text hide
  ```

## Set Font Size

Sizes = small, medium, big

- Syntax: `text size {sizes}`
- Example:

  ```txt
  text size big
  ```

## Set Typing Interval

Set how fast the typing effect. The smaller the value, the faster.

- Syntax: `text interval {seconde}`
- Example:

  ```txt
  text interval 0.02
  ```

## ~~Change Font~~

- Syntax: `text font {size}`
- Example:

  ```txt
  text font JiangChengYuanTi
  ```

## Rich Text

Support rich text operations, see [Unity UI Rich Text](https://docs.unity3d.com/Packages/com.unity.ugui@1.0/manual/StyledText.html "Unity UI Rich Text") for more information.

Aris Studio is being migrated to use [TextMeshPro (TMP)](https://docs.unity3d.com/Manual/com.unity.textmeshpro.html "TextMeshPro (TMP)"). For now, use Unity UI Rich Text to get rich text feature.

Currently available TMP Rich Text tags are: (Based on [TextMeshPro 4.0.0-pre.2](https://docs.unity3d.com/Packages/com.unity.textmeshpro@4.0/manual/RichTextSupportedTags.html))

| Tag: | Description: | Notes: |
|---|---|---|
| \<align\> | Changes the text's horizontal alignment. |  |
| \<allcaps\> | Converts text to uppercase before rendering. | Functionally identical to \<uppercase\>. |
| \<alpha\> | Changes text opacity. |  |
| \<b\> | Renders text in boldface. |  |
| \<br\> | Forces a line break in text. |  |
| \<color\> | Changes text color or color and opacity. |  |
| \<cspace\> | Changes spacing between characters. |  |
| \<font\> | Changes text font and, optionally, material. |  |
| \<font-weight\> | Changes the text's font weight to any of the weights defined in the font Asset. |  |
| \<gradient\> | Applies a gradient preset to text. |  |
| \<i\> | Renders text in italics. |  |
| \<indent\> | Indents all text between the tag and the next hard line break. |  |
| \<line-height\> | Modifies the line height relative to the default line height specified in the font Asset. |  |
| \<line-indent\> | Indents the first line after every hard line break. | New lines created by word-wrapping are not indented. |
| \<link\> | Specifies a link ID for a text segment. |  |
| \<lowercase\> | Converts text to lowercase before rendering. |  |
| \<margin\> | Gives the text horizontal margins. | You can set margins for both sides together or each side individually |
| \<mark\> | Highlights the text with a colored overlay. | The overlay must be translucent (alpha less than 1) for the text to show through. |
| \<mspace\> | Renders the text as monospace. |  |
| \<nobr\> | Keeps a segment of text together. |  |
| \<noparse\> | Prevents parsing of text that TextMesh Pro would normally interpret as rich text tags. |  |
| \<page\> | Adds a page break to the text. | The text's Overflow mode must be set to Page for page breaks to work. |
| \<pos\> | Sets the horizontal caret position on the current line. |  |
| \<rotate\> | Rotates each character about its center. |  |
| \<s\> | Renders a line across the text. |  |
| \<size\> | Adjusts the font size for a specified portion of the text. |  |
| \<smallcaps\> | Converts text to uppercase before rendering. |  |
| \<space\> | Adds a horizontal offset between itself and the rest of the text. |  |
| \<sprite\> | Adds a sprite to the text. | By default, TextMesh Pro looks in the default sprite assets, but you can use tag attributes to retrieve sprites from other assets. |
| \<strikethrough\> | Draws a line slightly above the baseline so it crosses out the text. |  |
| \<style\> | Applies a custom style to the text. |  |
| \<sub\> | Converts the text to subscript. |  |
| \<sup\> | Converts the test to superscript. |  |
| \<u\> | Draws a line slightly below the baseline to underline the text. |  |
| \<uppercase\> | Converts text to uppercase before rendering. | Functionally identical to \<allcaps\>. |
| \<voffset\> | Gives the baseline a vertical offset. |  |
| \<width\> | Changes the horizontal size of text area. |  |

See [TMP Rich Text Tags](https://docs.unity3d.com/Packages/com.unity.textmeshpro@4.0/manual/RichText.html "TMP rich text tags") to know more about those tags.
