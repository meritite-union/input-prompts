<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github_assets/cover_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="github_assets/cover_light.png">
  <img alt="The Meritite Union's Input Prompts" src="github_assets/cover.png">
</picture>

## 1000+ iconos vectoriales y rasterizados por todas sus necesidades de gamedev.
###### English [日本語](README.ja-jp.md)
Indicaciones de entrada del controlador ("**prompts**") de PlayStation, Xbox, y PC son listas y disponibles ahora.
Nintendo Switch prompts are in development.
Wii / Wii U, Steam Deck, generic, and more prompts are coming soon!

Hi! This asset pack was made by @hergergy as part of the Meritite Union.

Input Prompts is licensed under CC0 1.0 Universal. Permission is granted to use, distribute, and modify these resources. Attribution is not required, but always appreciated--publicity is the best support. Right now this project is not tied to anything official, so I would appreciate simply coming back later at future projects.

This project is directly inspired by [Kenny’s Input Prompts](https://www.kenney.nl/assets/input-prompts). [Xelu’s](https://thoseawesomeguys.com/prompts/) too. If you don’t like mine, check out theirs!

# Guide
## "Installation"
Everything you need is included in a single `.zip` file. Download the [latest version](https://github.com/meritite-union/input-prompts/releases/latest) from any of the published sources and you should be good to go. 
## Folder Structure
The file structure is `format / platform / theme / category / subcategory / shade / variant.format`, where:
- `format`: `256-png` for 256x256px png images (2x upscale from Figma) or `svg` for vector graphics (at standard 128x128 1x scale).
- `platform`: `xbox`, `ps` for PlayStation, or `pc` for Keyboard / Mouse for now.
- `theme`: `light` or `dark`.
- `category`: This varies by platform. It is simply a group of related prompts.
- `subcategory`: Same as `category`. Not all categories are subcategorized.
- `shade`: In prompts depicting a single control, `_` and `fill`. The fill variant is intended for showing an active pressed state. In other categories where multiple controls are depicted, like `dpad` or `mouse`, this is covered by variants.
- `variant`: The file itself is named based on the specific control or variant that the prompt depicts.

This has some implications which may impact how you use these assets.
- File names themselves are not necessarily unique—the folder structure is necessary information in the prompt's meaning. Both the D-pad up and left stick up have the same file name, `w.svg`, but are only distinguished by their location.
- By extension, the images themselves may not be unique. The pack is designed to have all assets of a platform be self-contained within the respective platform folder, even if that means the same prompt is stored multiple times. For example, if you are developing a game for Xbox only, you would be able to find the left stick prompts in the `xbox` folder, even if the PlayStation left stick prompts are identical.
## File Format
The following information relates to the `.svg` format.

All prompts fit within a 128x128 bounding box. Stroke width is generally 6 pixels. Standard colors used include ![#191923 HEX color representation](github_assets/191923.svg) `#191923`, ![#2E2836 HEX color representation](github_assets/2e2836.svg) `#2E2836`, ![#C8CED0 HEX color representation](github_assets/c8ced0.svg) `#C8CED0`, and ![#FBFEF9 HEX color representation](github_assets/fbfef9.svg) `#FBFEF9`. These colors correspond to the standard Meritite Union grayscale colors, although they might not match your brand or game. You might have some SVG automation tool I'm unaware of, but if you need to make changes, I recommend modifying and exporting the icons from the [Figma file](https://www.figma.com/community/file/1354930683181049242/input-prompts) directly. Another thing to note is that the Xbox and PlayStation colored prompts **do not** match the official brand colors, instead they are based on the Meritite Union colors. This is to avoid potential trademark infringement.

To try to help with import to whatever system you're using, I've formatted the file names to try to avoid your tools from throwing a fit. File and folder names consist of only lowercase a-z, underscore, and digits 0-9, although no file name begins with a digit. I'm not particularly experienced in these things, and I've only used a handful of tools. If there's a better format, please [let me know](https://github.com/meritite-union/input-prompts/issues/new)! Similarly, please leave an issue for any kind of feedback.
\
\
\
<img src="https://github.com/meritite-union/brand/blob/c0399ebfb77d66757c189edf77639b8a349f1d62/250x250.svg" width="35" height="35" alt="Meritite Union plain purple squid mascot" style="float:right;">
