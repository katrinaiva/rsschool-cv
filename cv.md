# Ekaterina Ivantseva

#### Contacts for communication

email: **ivaka3na@gmail.com**;\
skype: **katrina_i87**;\
tel: **+375297552301**;

---

#### Summary

Experience in IT industry more 3 years as HTML-developer that includes developing responsive layouts of webpages and apps using standard HTML5/CSS3 practices. Skilled in development of semantic HTML markup according to W3C standards with cross-browser compatibility. I come up with a great responsibility to all the projects, trying to find the most suitable solution.

---

#### Knowledge and Skills

- **Technologies and frameworks:**\
  HTML(5), CSS(Less/Sass), Grunt/Gulp, Webpack, Bootstrap, Javascript and jQuery, Angular2+
- **CSS methodologies:**\
  SMACSS, BEM
- **Tools and middleware:**\
  Git, SVN, Jira, Adobe Photoshop, Figma, Adobe Illustrator, Web Storm, VSCode.

---

#### Code examples

```
var getRandomInt = function (min, max) {
  return Math.floor(Math.random() * (max + 1 - min)) + min;
};

var getRandomItem = function (items) {
  return items[getRandomInt(0, items.length - 1)];
};

var getWizardItem = function () {
  return {
    name: getRandomItem(NAMES) + ' ' + getRandomItem(SURNAMES),
    coatColor: getRandomItem(COAT_COLORS),
    eyesColor: getRandomItem(EYES_COLORS),
  };
};

var wizards = [];

for (var j = 0; j < 4; j++) {
  wizards.push(getWizardItem());
}

var similarListElement = document.querySelector('.setup-similar-list');
var wizardTemplate = document.querySelector('#similar-wizard-template').content.querySelector('.setup-similar-item');
var wizardFragment = document.createDocumentFragment();

for (var i = 0; i < 4; i++) {
  var wizardElement = wizardTemplate.cloneNode(true);
  wizardElement.querySelector('.setup-similar-label').textContent = wizards[i].name;
  wizardElement.querySelector('.wizard-coat').style.fill = wizards[i].coatColor;
  wizardElement.querySelector('.wizard-eyes').style.fill = wizards[i].eyesColor;
  wizardFragment.appendChild(wizardElement);
}

similarListElement.appendChild(wizardFragment);
```

---

#### Work Experience

HTML-developer more 3 yers.

**Courses, certificates**

- HTML & CSS base course (html Academy). Educational projects: [Sedona](https://katrinaiva.github.io/188118-sedona/) and [Nerds](https://katrinaiva.github.io/188118-nerds/).

- HTML & CSS advanced course (html Academy). Educational project [Pink](https://katrinaiva.github.io/188118-pink/)

---

#### Education

Belarusian State University of Informatics and Radioelectronics \
**Specialization**: Multichannel system of telecommunications.

---

#### Foreign languages

• English – Pre-Intermediate.
