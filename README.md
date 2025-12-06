<br>

<div align="center" style="background:#1B1A29; padding:20px 40px; border-radius:16px; display:inline-block; box-shadow:0 0px 0px rgba(0,0,0,0.4);">

  <!-- Icon -->
  <img src="./icon/icon.png" width="100" style="border-radius:12px; margin-bottom:12px;"/>

  <!-- Title -->
  <p style="font-size:20px; color:#b0c4dd; margin:12px 0 20px 0;">
    CozyCat for VSCode
  </p>

  <!-- Badges -->
  <div style="display:flex; gap:6px; justify-content:center; flex-wrap:wrap; margin-bottom:16px;">
    <img src="https://img.shields.io/github/stars/ayusshere/cozycat-theme?style=for-the-badge&colorA=3b88b8&colorB=60b2e1"/>
    <img src="https://img.shields.io/github/issues/ayusshere/cozycat-theme?style=for-the-badge&colorA=dd99c9&colorB=f5c2e7"/>
    <img src="https://img.shields.io/github/contributors/ayusshere/cozycat-theme?style=for-the-badge&colorA=78c170&colorB=aae484"/>
  </div>

  <!-- Palette -->
  <div style="display:flex; justify-content:center; flex-wrap:wrap; gap:2px;">
    <span style="display:inline-block; width:20px; height:20px; background:#f5e0dc;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#f2cdcd;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#f5c2e7;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#dd99f4;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#e27882;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#fd9db2;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#fbb470;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#f0e893;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#aae484;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#94e2d5;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#89dceb;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#74c7ec;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#60b2e1;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#b4befe;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#b0c4dd;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#9ca2bb;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#9399b0;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#767b8b;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#565866;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#54586c;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#3e404f;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#2b2c3b;"></span>
    <span style="display:inline-block; width:20px; height:20px; background:#1B1A29;"></span>
  </div>

</div>

---

<p align="center"> CozyCat is a <b>warm, calm, and elegant dark theme</b> for Visual Studio Code, designed to make coding comfortable and enjoyable for long sessions.
With soft colors and subtle contrasts, CozyCat reduces eye strain while keeping your code readable and beautiful.
</p>

---

## Features

- Dark, soothing color palette  
- Carefully selected syntax highlighting for better readability  
- Minimalistic UI elements for a distraction-free experience  
- Eye-friendly design for long working hours  

---

## Screenshots

*(Add screenshots in your project folder)*

![Editor Screenshot](./screenshots/editor.png)  
![Sidebar Screenshot](./screenshots/sidebar.png)

---

## Installation

### From Marketplace  
(Once published) search for **CozyCat** in the Extensions panel.

### From VSIX  
1. Open **Command Palette → Extensions: Install from VSIX...**  
2. Select your `.vsix` file  
3. Go to **Preferences → Color Theme → choose CozyCat**

---

## Usage

To activate the theme:  
**Command Palette → Preferences: Color Theme → CozyCat**

Enjoy a clean, calm, cozy coding environment.

---

## Customization

You can style different parts of your code—like comments, keywords, or function names—using **italic**, **bold**, **both**, or leave them normal.  
If you don’t want any style, just use `""`.

### How it works

- **scope** → Defines which part of your code the style applies to  
  - Examples: `"comment"`, `"keyword"`, `"entity.name.function"`  
- **fontStyle** → Defines the style applied to that scope  
  - `"italic"` → makes text italic  
  - `"bold"` → makes text bold  
  - `"italic bold"` → both italic and bold  
  - `""` → normal (no style)  

You can combine multiple scopes in a single block.

### Example

```jsonc
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "comment",           
            "settings": { "fontStyle": "italic" }  
        },
        {
            "scope": "keyword",           
            "settings": { "fontStyle": "bold" }  
        },
        {
            "scope": "entity.name.function",  
            "settings": { "fontStyle": "italic" }  
        }
    ]
}
```

## Contributing

Pull requests and suggestions are welcome.  
Feel free to open issues for improvements or new feature ideas.


## License

[MIT License](./LICENSE)


## About the Author  
Made with ❤️ by [Ayush Namdev](https://github.com/ayusshere)
