# Solar System Explorer 🪐

**Explore the cosmos with just HTML and CSS!** This single-page web application is an interactive and educational journey through our solar system, demonstrating the incredible power of pure CSS.

---

## 🚀 Key Features

* **100% CSS-Powered:** No JavaScript was used to create the dynamic interactions, animations, or content display.
* **Interactive Menu:** Select a planet from the menu to zoom in and explore it in detail.
* **3D Space Simulation:** Experience a sense of depth and perspective with CSS 3D transforms.
* **Continuous Animations:** Watch planets rotate on their axes and moons orbit their celestial bodies, all driven by CSS animations.
* **Detailed Information Panels:** Click "Read More" to reveal a wealth of information about each planet.

---

## ✨ How It Works

This project is a masterclass in creative CSS techniques:

* **Hidden Radio Buttons:** Each planet is tied to a hidden `<input type="radio">`.
* **The `:checked` Selector:** When you click a planet's name (which is a `<label>`), the corresponding radio button becomes checked.
* **CSS Sibling Selectors (`~` and `+`):** These powerful selectors target and style elements that appear after the checked radio button. This is the secret to:
    * **Dynamic View:** The entire solar system shifts and transforms, bringing your selected planet to the front.
    * **Showing/Hiding Content:** The "Read More" panels are hidden by default and are only displayed when their corresponding radio button is checked.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Google Fonts:** Montserrat
* **Font Awesome:** For icons

---

## 📖 Usage

Simply open the `index.html` file in your web browser. Click on any planet name in the left-hand menu to start your adventure!

---

## 🙏 Acknowledgements

This project was created by Nitesh Shaw, inspired by the vast and beautiful universe and the limitless potential of CSS.
