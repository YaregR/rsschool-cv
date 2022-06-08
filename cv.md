# Yaroslav Rudenko

### Junior Frontend Developer

---

### Contacts:

**Location:** Kyiv, Ukraine<br>
**Phone:** +38 067 121-43-01<br>
**E-mail:** yaregr@gmail.com<br>
**LinkedIn:** [Yaroslav Rudenko](https://www.linkedin.com/in/yaroslav-rudenko-a7107655/)<br>

### About Me:

My goal is to learn full stack development (MERN) and create interesting and useful applications.<br>

### Skills:

- HTML5, CSS3
- JavaScript Basics
- NodeJS
- Git, GitHub
- Adobe Photoshop, Illustrator, CorelDraw, Figma

### Code Example:

```
let form = document.forms.calculator;
let resEl = document.querySelector('.result span');
let multiplyBtn = document.querySelector('.multiplyBtn');

multiplyBtn.addEventListener('click', (ev) => {
    ev.preventDefault();

    let formData = new FormData(form);

    let number1 = formData.get('number1');
    let number2 = formData.get('number2');
    let digits = formData.get('digits');

    let res = number1 * number2;
    let resDigit = Number (res.toFixed(digits));
    resEl.innerHTML = resDigit;
});
```
