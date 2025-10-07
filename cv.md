# Majid M. M. Zanjani

![Majid Zanjani](./photo.png)

**Front-End Developer**

**Contact**

- Phone: +995 551 100 642
- Email: [majidmmz1972@gmail.com](mailto:majidmmz1972@gmail.com)
- Discord: Majid Zanjani (@MajidZanjani)
- Location: Tbilisi, Georgia

---

## Summary

Motivated Front-End Developer with hands-on experience in building responsive web applications using JavaScript, TypeScript, React, HTML, and CSS. Skilled in problem-solving and eager to learn new technologies. Brings additional knowledge in IT support, databases, and cloud platforms, combined with strong teamwork and communication skills. Looking for opportunities to grow as a developer while contributing to innovative projects.

---

## Skills

**Programming:** JavaScript, TypeScript, CSS, Tailwind CSS, HTML  
**Frameworks:** React, React Router, Angular  
**Platforms:** Windows, Linux

**ServiceNow:** Studio, ITSM, Tables & Forms, Workflows, Client & Server Scripts, Catalog Items

**Other IT Skills:** Figma, AWS, Git, CI/CD pipelines, DevOps, MySQL, PostgreSQL, Kubernetes, Docker

**Personal Skills:** Reliable teammate, Communication, Documentation, Eager to Learn, Detail-oriented, Project Management

---

## Languages

- English – B2
- German – A1
- Persian – Native

---

## Find Me Online

- [GitHub](https://github.com/MajidZanjani/)
- [LinkedIn](https://www.linkedin.com/in/majidzanjani/)
- [Portfolio](https://myportfolio-mz.netlify.app/)
- [Portfolio GitHub](https://github.com/MajidZanjani/myportfolio)
- [ServiceNow](https://nowlearning.servicenow.com/lxp/en/pages/nl-public-resume?id=nl_public&user=majidmmz)

---

## Experience

**ServiceNow Developer Trainee** | _EPAM Campus – ServiceNow Q1-25_  
Tbilisi, Georgia | _04/2025 – 09/2025_

- Completed hands-on ServiceNow training program focused on ITSM, workflows, and custom application development using JavaScript.

**Front-End Developer** | _Synaptic Laboratories LTD_  
Tbilisi, Georgia | _01/2021 – 04/2025_

- Implemented dynamic website features using JavaScript, CSS, and HTML, increasing user engagement.
- Handled website administration and support on AWS.

---

## CodeWars Example

```javascript
const Mongo = {
  isValid: function (id) {
    return (
      typeof id === "string" && /^[0-9a-f]{24}$/.test(id) // exactly 24 hex chars
    );
  },

  getTimestamp: function (id) {
    if (!this.isValid(id)) return false;

    // First 8 chars = 4 bytes = Unix timestamp (in seconds)
    const timestampHex = id.slice(0, 8);
    const timestampSeconds = parseInt(timestampHex, 16);

    // Convert to Date (JS expects ms, so multiply by 1000)
    return new Date(timestampSeconds * 1000);
  },
};
```

[View on CodeWars](https://www.codewars.com/kata/52fefe6cb0091856db00030e/solutions/javascript?filter=me&sort=best_practice&invalids=false)
