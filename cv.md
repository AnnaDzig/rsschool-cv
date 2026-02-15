## [Dzhyhota Anna](https://github.com/AnnaDzig)

**A student of The Rolling Scopes School**

---

### Contacts:

- Denmark, 6000, Kolding;
- Email Address: anna.soft.dev@gmail.com;
- Phone: 26 66 12 59;

### About Me

Passionate software developer with a strong foundation in front-end and full-stack development. Skilled in JavaScript, TypeScript, React, React Native, Next.js, Node.js, MySQL, MongoDB, C#, and .NET. Experienced in building scalable applications, integrating complex systems, and improving user experiences. Committed to continuous learning and creating impactful software solutions.

### Education

_BACHELOR'S DEGREE IN GEODESY AND LAND MANAGEMENT_ **Pylyp Orlyk International Classical University**

_MASTER'S DEGREE IN SOCIAL WORK_ **Petro Mohyla Black Sea National University**

### Additional Education

- [Rolling Scopes School stage#0](https://rs.school/)
- [C# / .NET DEVELOPER CyberBionic Systematics](https://cbsystematics.com/)
- [WEB DEVELOPMENT (BOOTCAMP) HackYourFuture](https://www.hackyourfuture.dk)

### The code Example

_Navbar Effect_

```javascript
const fullImg = document.querySelector(".full-img");
const smallImg = document.querySelectorAll(".gallery img");
const modal = document.querySelector(".modal");

// console.log(smallImg);
smallImg.forEach(function (img) {
  img.addEventListener("click", function () {
    modal.classList.add("open");
    fullImg.classList.add("open");

    // Changin' the images dynamically
    const originalQuality = img.getAttribute("alt");
    fullImg.src = `img/full/${originalQuality}.jpg`;
  });
});

modal.addEventListener("click", function (e) {
  if (e.target.classList.contains("modal")) {
    modal.classList.remove("open");
    fullImg.classList.remove("open");
  }
});
```

### Language Skills:

| **Language** | **Level**                       |
| ------------ | ------------------------------- |
| English      | Full Professional Proficiency   |
| Danish       | Intermediate Proficiency        |
| Polish       | Advanced Proficiency            |
| Ukraine      | Native or Bilingual Proficiency |
| Russian      | Native or Bilingual Proficiency |

---

![Logo rsshool ](https://images.ctfassets.net/12phxmr4hjo6/1smXnLTHAHCOfscGaaxaN3/c9316b79ec5cde3749b6d1e6601b60d8/RsBanner.svg "Logo rsshool")
