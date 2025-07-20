# photograpgy-UI-sidebar-menu 📸

A clean and responsive **Sidebar UI** built using only **HTML & CSS** — with a photography-themed design and a toggle-based sidebar menu. Fully responsive for portrait and landscape modes.

---

## ✨ Features

- 📱 **Responsive Sidebar** – Appears from the left pane using checkbox + label toggle.
- 🍔 **Hamburger & Cross Icons** – Professionally styled icons controlled by checkbox state.
- 🎨 **Modern UI** – Uses a grey shaded layout with an elegant background photography image.
- 🖱️ **Hover Effects** – Sidebar menu items glow in whitish shade on hover.
- 🧭 **Sticky Bottom Icons** – Hamburger/Cross icons remain at the bottom corner responsively.
- ⚙️ **No JavaScript Used** – Entire functionality achieved using HTML and CSS only.

---

## 📸 Demo Screenshots

> 🔻 Portrait Mode  
![Portrait Sidebar](https://github.com/Ankit-Raj902/photograpgy-UI-sidebar-menu/blob/77fb3eb0bf6c12e0dc5139244e5b2c71068c2af0/Screenshot_20250720-092906_WebCode.jpg)

> 🔁 Landscape Mode  
![Landscape Sidebar](https://github.com/Ankit-Raj902/photograpgy-UI-sidebar-menu/blob/77fb3eb0bf6c12e0dc5139244e5b2c71068c2af0/Screenshot_20250720-092856_WebCode.jpg)

*(Optional: You can also embed demo GIFs or YouTube video links)*

---

## 🛠️ Built With

- **HTML5**
- **CSS3 (Flexbox + Media Queries + Checkbox Hack)**

---

## 🚀 How It Works

Checkbox is used to toggle sidebar:

```css
/* Default icon display */
.icon1 {
  display: inline;
}
.icon2 {
  display: none;
}

/* Toggle icons when menu is checked */
#menu-toggle:checked + label .icon1 {
  display: none;
}
#menu-toggle:checked + label .icon2 {
  display: inline;
}

