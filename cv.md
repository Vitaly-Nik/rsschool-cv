# Vitaly Nikitsenkau
---
## Contacts

- **e-mail:** nikitalik93@mail.ru
- **discord:** Vitaly-Nik (@Vitaly-Nik)
- **tel:** +375(29)222-66-00

---

## Summary

I am 28 y.o. and for now I am an aspiring front-end developer. My specialty is infocommunication systems engineer. I have been working as a system administrator of computer networks for 3 years. Мy further goal is to progress in front-end development.

---
## Skills

### Hard Skils

- HTML/CSS
- Git
- JS
- Linux

### Soft Skils

- Sociability
- Friendliness
- Ability to work in a team

---
## Sample code

```

  let headingTableBuyPrice = document.querySelector(
    "table.table.table-responsive.table-bordered.table-hover.table-striped"
  ).children[0].children[0].children[2].innerText;
  document.querySelector(
    "table.table.table-responsive.table-bordered.table-hover.table-striped"
  ).children[0].children[0].children[2].innerText = `${headingTableBuyPrice}\n(Desired Selling Price)`;

  let allStringItemBuyPrice = document.querySelector(
    "table.table.table-responsive.table-bordered.table-hover.table-striped"
  ).children[0].children;

  let h = 1;
  while (h >= 1 && h <= allStringItemBuyPrice.length - 1) {document.querySelector(
      "table.table.table-responsive.table-bordered.table-hover.table-striped"
    ).children[0].children[h].children[2].className = "text-center";

    let itemBuyPrice = document.querySelector("table.table.table-responsive.table-bordered.table-hover.table-striped").children[0].children[h].children[2].innerText;

    let stateByOrder = document.querySelector("table.table.table-responsive.table-bordered.table-hover.table-striped").children[0].children[h].children[3].innerText;

    if (stateByOrder === "Active") {
      let numberItemBuyPrice = itemBuyPrice.substring(1, itemBuyPrice.length);
      let desSelPrice = ((numberItemBuyPrice * 100) / 95.05).toFixed(2);

      document.querySelector(
        "table.table.table-responsive.table-bordered.table-hover.table-striped"
      ).children[0].children[h].children[2].innerText = `${itemBuyPrice} | (>$${desSelPrice})`;
    }
    h = h + 1;
  }
```

---
## Education

- Cisco Certified Network Associate (CCNA) Routing and Switching
- Belarusian State Academy of Telecommunications - Infocommunication Systems Engineer
- [HTML For beginners](https://ru.code-basics.com/laguages/html)
- [CSS For beginners](https://ru.code-basics.com/languages/css)
- [JS For beginners](https://ru.code-basics.com/languages/javascript)
- [Freelancer Life Style (HTML,CSS, js)](https://www.youtube.com/c/FreelancerLifeStyle)

---

## English level

**At the moment my level is A2**
