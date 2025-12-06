<br>

<p align="center">
  <img src="./icon/icon.png" width="130"/>
</p>

<p align="center" style="font-size: 22px;">
  <b>CozyCat</b> for VSCode
</p>

<p align="center">
  <!-- GitHub Stats -->
  <img src="https://img.shields.io/github/stars/ayusshere/cozycat-theme?style=for-the-badge&colorA=3b88b8&colorB=60b2e1"/>
  <img src="https://img.shields.io/github/issues/ayusshere/cozycat-theme?style=for-the-badge&colorA=dd99c9&colorB=f5c2e7"/>
  <img src="https://img.shields.io/github/contributors/ayusshere/cozycat-theme?style=for-the-badge&colorA=78c170&colorB=aae484"/>
</p>

---

<p align="center"> CozyCat is a <b>warm, calm, and elegant dark theme</b> for Visual Studio Code, designed to make coding comfortable and enjoyable for long sessions.
With soft colors and subtle contrasts, CozyCat reduces eye strain while keeping your code readable and beautiful.
</p>

---

## Palette

<div align="center" style="display:flex; gap:12px; flex-wrap:wrap; justify-content:center;">
  <div style="background:#f5e0dc; width:20px; height:20px;"></div>
  <div style="background:#f2cdcd; width:20px; height:20px;"></div>
  <div style="background:#f5c2e7; width:20px; height:20px;"></div>
  <div style="background:#dd99f4; width:20px; height:20px;"></div>
  <div style="background:#e27882; width:20px; height:20px;"></div>
  <div style="background:#fd9db2; width:20px; height:20px;"></div>
  <div style="background:#fbb470; width:20px; height:20px;"></div>
  <div style="background:#f0e893; width:20px; height:20px;"></div>
  <div style="background:#aae484; width:20px; height:20px;"></div>
  <div style="background:#94e2d5; width:20px; height:20px;"></div>
  <div style="background:#89dceb; width:20px; height:20px;"></div>
  <div style="background:#74c7ec; width:20px; height:20px;"></div>
  <div style="background:#60b2e1; width:20px; height:20px;"></div>
  <div style="background:#b4befe; width:20px; height:20px;"></div>
  <div style="background:#b0c4dd; width:20px; height:20px;"></div>
  <div style="background:#9ca2bb; width:20px; height:20px;"></div>
  <div style="background:#9399b0; width:20px; height:20px;"></div>
  <div style="background:#767b8b; width:20px; height:20px;"></div>
  <div style="background:#565866; width:20px; height:20px;"></div>
  <div style="background:#54586c; width:20px; height:20px;"></div>
  <div style="background:#3e404f; width:20px; height:20px;"></div>
  <div style="background:#2b2c3b; width:20px; height:20px;"></div>
  <div style="background:#1B1A29; width:20px; height:20px;"></div>
</div>


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


## Installation

### From Marketplace  
(Once published) search for **CozyCat** in the Extensions panel.

### From VSIX  
1. Open **Command Palette → Extensions: Install from VSIX...**  
2. Select your `.vsix` file  
3. Go to **Preferences → Color Theme → choose CozyCat**


## Usage

To activate the theme:  
**Command Palette → Preferences: Color Theme → CozyCat**

Enjoy a clean, calm, cozy coding environment.


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
            "scope": "comment",           // Comments like // or /* */
            "settings": { "fontStyle": "italic" }  
        },
        {
            "scope": "keyword",           // Keywords like if, for, return
            "settings": { "fontStyle": "bold" }  
        },
        {
            "scope": "entity.name.function",  // Function names like myFunction()
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
