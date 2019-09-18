# Kirill Shumakov

## Contacts
* **Phone**: +79042650540
* **E-mail**: deviant1967@gmail.com
* **VK**: [Kirill Shumakov](https://vk.com/hierumo)

## About Me
> Versatile well-organized frontend-trainee with 8+ month of experience designing, developing some kind of best code ever (among trainees of course). My main goal is to get as much new knowledge as possible, cuz I wanna become the best (or at least a good one) frontend-engineer.

## Skills
* Programming languages and technologies: ECMAScript-7, HTML5, CSS3/Less, Delphi 7, Pascal, Basic, a lil' bit Lua
* Frameworks: a lil' bit experience of using React, jQuery, Redux
* Tools: VS Code, Chrome Dev Tools, GIT Terminal
* Other skills: driving experience 8 years, masterly command of Russian obscene language so I'm so *sociable*, and dunno, Night Elf Hunter 60 at WoW Classic is it worth?

## Code examples
```javascript
(function trader() {
    "use strict";
    let calculate = document.body.querySelector('.calculate');
    let clear = document.body.querySelector('.clear');
    let result = document.body.querySelector('.result');
    let text = document.body.querySelector('.text');

    calculate.onclick = (e) => {

        let jewelToChaos = document.getElementById('jewelToChaos').value;
        let chaosToFusing = document.getElementById('chaosToFusing').value;
        let jewelToFusing = document.getElementById('jewelToFusing').value;
        e.preventDefault();
        result.textContent = jewelToChaos * chaosToFusing;

        let message = "Buy chaos orbs first";
        if (jewelToChaos * chaosToFusing < jewelToFusing) {
            message = "Buy fusing orbs";
        }
        text.textContent = message;
    };
    clear.onclick = (e) => {
        result.textContent = "";
        text.textContent = "";
    };
}());
```

## Professional Experience
* actually, I never was in commercial development
* but in my Past I was worked for the bug-tracking system OOO Keysystems for budget-accounting app as a tester
* freelancing as content-manager

## Education
* **Penza State Technological University**  - Specialist economist-manager (graduated in 2013)

## English
Upper Intermediate (B2)
