![new-photo](https://user-images.githubusercontent.com/26907855/132730317-03675c8d-fdce-41ab-9a79-c5bb9c22ecda.jpg)


# Koval Sergey

## Contact info

- **Email:** hdmaxset@gmail.com
- **Github:** @MaxSettings
- **Telegram:** @slntLurker

## About me

I have a goal to become a highly skilled frontend developer. Most of my knowledge in this area came from self-study. I like Web development and I have already managed to learn a lot of information and got a lot of practice, both during studying and during work. And now I continue to study in order to improve myself and use the most relevant technologies and practices.

## Technical Skills

- HTML
- CSS
- JS (basics)
- BEM
- SASS, SCSS
- Git
- Gulp
- Figma, Avocode, Photoshop
- VS Code, WebStorm

## Code example

```javascript
function decoder(sequence) {
  let res = [];
  let zeroesCount = 0;

  for (let i = 0; i < sequence.length; i++) {
    if (sequence[i] === "0") {
      zeroesCount++;
    } else {
      res.push(parseInt(sequence.slice(i, i + zeroesCount + 1), 2) - 1);
      i += zeroesCount;
      zeroesCount = 0;
    }
  }

  return res;
}
```

## Work Experience

I have about a year of web development experience. Almost all this time I have been working in a small company that develop websites for state institutions. I know what semantic, responsive and cross-browser development is and I can work with layouts in Figma and Photoshop. I have experience writing basic JavaScript logic (such as creating sliders, modals, burger-menus), working in a React project, and building a project component library.

## Education

In 2020, I graduated as a master's degree from Donetsk National Technical University (Faculty of Computer Science and Technology, Software Engineering).

## English level

According to the site [Ef Set](https://www.efset.org/ru/), my level of English is in the range from B1 to B2. I can use the documentation in English without any problems and I know many terms related to IT and Web-development. I am still continuing to improve my English.
