<div align="center">

  <!-- Icon -->
  <img src="./icon/icon.png" width="100" style="border-radius:12px; margin-bottom:0px;"/>

  <!-- Title -->
  <h1 style="font-size:20px; color:#b0c4dd; margin:12px 0 20px 0;">
    CozyCat for <a href="https://code.visualstudio.com">VSCode</a>
  </h1>

  <!-- Badges -->
  <div style="display:flex; gap:6px; justify-content:center; flex-wrap:wrap; margin-bottom:16px;">
    <img src="https://img.shields.io/github/stars/ayusshere/cozycat-theme?style=for-the-badge&colorA=3b88b8&colorB=60b2e1"/>
    <img src="https://img.shields.io/github/issues/ayusshere/cozycat-theme?style=for-the-badge&colorA=dd99c9&colorB=f5c2e7"/>
    <img src="https://img.shields.io/github/contributors/ayusshere/cozycat-theme?style=for-the-badge&colorA=78c170&colorB=aae484"/>
  </div>

</div>

---

<p align="center"> CozyCat is a <b>warm, calm, and elegant dark theme 🌙</b> for Visual Studio Code, designed to make coding comfortable and enjoyable for long sessions.  
With soft colors and subtle contrasts, CozyCat reduces eye strain 👀 while keeping your code readable and beautiful 🎨.
</p>

---

## Features ✨

- 🌑 Dark, soothing color palette  
- 🎯 Carefully selected syntax highlighting for better readability  
- 🧘 Minimalistic UI elements for a distraction-free experience  
- 🖥️ Eye-friendly design for long working hours  

---

## Preview 👀
<p align="center">

![Editor Screenshot](demo/motion.gif)  

</p>

### Language-wise Examples 💻

<details>
<summary>Python 🐍</summary>
<img src="demo/python.png" alt="Python Example"/>
</details>

<details>
<summary>JavaScript ⚡</summary>
<img src="demo/js.png" alt="JavaScript Example"/>
</details>

<details>
<summary>Java ☕</summary>
<img src="demo/java.png" alt="Java Example"/>
</details>

<details>
<summary>C++ 💻</summary>
<img src="demo/cpp.png" alt="C++ Example"/>
</details>

<details>
<summary>HTML 🌐</summary>
<img src="demo/html.png" alt="HTML Example"/>
</details>

<details>
<summary>CSS 🎨</summary>
<img src="demo/css.png" alt="CSS Example"/>
</details>

<details>
<summary>Go 🐹</summary>
<img src="demo/go.png" alt="Go Example"/>
</details>

<details>
<summary>Rust 🦀</summary>
<img src="demo/rust.png" alt="Rust Example"/>
</details>

<details>
<summary>JSON 📄</summary>
<img src="demo/json.png" alt="JSON Example"/>
</details>

---

## Installation 🚀

### From Marketplace  
(Once published) search for **CozyCat** in the Extensions panel.

### From VSIX  
1. Open **Command Palette → Extensions: Install from VSIX...**  
2. Select your `.vsix` file  
3. Go to **Preferences → Color Theme → choose CozyCat**

---

## Usage 🎛️

To activate the theme:  
**Command Palette → Preferences: Color Theme → CozyCat**

Enjoy a clean, calm, cozy coding environment 😺.

---

## Customization 🎨

You can style different parts of your code—like comments, keywords, or function names—using **italic**, **bold**, **both**, or leave them normal.  
If you don’t want any style, just use `""`.

### How it works ⚙️

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

## My Configuration

Font Source - [Maple Mono](https://font.subf.dev/en/)
<br>Icon Theme - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
``` jsonc
    "editor.fontFamily": "Maple Mono NF,JetBrainsMono Nerd Font",
    "editor.fontSize": 20.5,
    "editor.fontLigatures": "'calt','ss11','ss06','ss10','ss03'",
    "editor.lineNumbers": "relative",
    "editor.cursorBlinking": "expand",
    "terminal.integrated.fontSize": 17,

```


## Contributing

Pull requests and suggestions are welcome.  
Feel free to open issues for improvements or new feature ideas.


## License

[MIT License](./LICENSE)


## About the Author  
Made with ❤️ by [Ayush Namdev](https://github.com/ayusshere)
