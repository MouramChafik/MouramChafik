<div align="center">

# Chafik Mouram
### QA Engineer · Test Automation Specialist · Full-Stack Developer

[![Portfolio](https://img.shields.io/badge/Portfolio-mouram.netlify.app-0F6E56?style=flat-square&logo=netlify)](https://mouram.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-chafik--mouram-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/chafik-mouram/)
[![GitHub](https://img.shields.io/badge/GitHub-MouramChafik-181717?style=flat-square&logo=github)](https://github.com/MouramChafik)
[![Email](https://img.shields.io/badge/Email-mouram.chafik@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:mouram.chafik@gmail.com)

📍 Lyon, France &nbsp;·&nbsp; 🌍 FR · EN · AR · IT &nbsp;·&nbsp; 🚗 Permis B

</div>

---

## 🎯 Profil

QA Engineer passionné par la **qualité logicielle** et l'**automatisation des tests**. Certifié **ISTQB**, je conçois des stratégies de test robustes couvrant les niveaux unitaire, intégration et E2E. Mon background full-stack (React / Node.js) me permet de comprendre l'ensemble du cycle de développement, de détecter les points de friction tôt, et de collaborer efficacement avec les équipes dev et produit.

> *"Quality is not an act, it is a habit."* — Aristote

---

## 🧪 Expertise QA & Automatisation

| Framework | Niveau | Domaine |
|---|---|---|
| 🎭 **Playwright** | ⭐⭐⭐⭐⭐ | E2E · Multi-navigateurs · CI/CD |
| 🌲 **Cypress** | ⭐⭐⭐⭐⭐ | E2E · Intégration · Tests de composants |
| 🤖 **Robot Framework** | ⭐⭐⭐⭐ | Keyword-driven · BDD · Acceptance testing |
| 🕸️ **Selenium** | ⭐⭐⭐⭐ | WebDriver · Tests cross-plateforme |
| 🔬 **Jest / Vitest** | ⭐⭐⭐⭐ | Tests unitaires · TDD · Mocking |
| 📬 **Postman** | ⭐⭐⭐⭐ | API testing · Tests de contrat & régression |

**Méthodologie** : ISTQB · Test Plans · Bug Reporting · Test Coverage · Functional Testing · Regression Testing

---

## ⚙️ Pipeline de tests type

```
Analyse → Plan de test → Tests unitaires → Intégration → E2E → CI/CD → Rapport
```
---

## 💡 Exemple — Test Cypress (JavaScript)

```javascript
it('user can add a product to the cart', () => {
  cy.visit('/products');

  cy.get('[data-testid="product-card"]').first().within(() => {
    cy.get('[data-testid="product-title"]').should('be.visible');
    cy.get('[data-testid="add-to-cart-btn"]').click();
  });

  cy.get('[data-testid="cart-count"]').should('contain', '1');
  cy.get('[data-testid="cart-icon"]').click();

  cy.url().should('include', '/cart');
  cy.get('[data-testid="cart-item"]').should('have.length', 1);
});
```

## 💡 Exemple — Test Playwright (TypeScript)

```typescript
import { test, expect } from '@playwright/test';

test('user can log in successfully', async ({ page }) => {
  await page.goto('/login');
  await page.fill('[data-testid="email"]', 'user@example.com');
  await page.fill('[data-testid="password"]', 'securepassword');
  await page.click('[data-testid="submit"]');

  await expect(page).toHaveURL('/dashboard');
  await expect(page.locator('h1')).toContainText('Welcome');
});
```

---

## 💻 Stack technique complète

**🧪 QA & Automatisation**
`Playwright` `Cypress` `Selenium` `Robot Framework` `Jest` `Vitest` `Postman` `ISTQB`

**🎨 Frontend**
`React` `TypeScript` `JavaScript` `HTML5` `CSS3` `Tailwind CSS` `Material-UI` `React Router`

**⚙️ Backend**
`Node.js` `Express.js` `MySQL` `REST API`

**🛠️ Outils**
`Git` `GitHub` `Figma` `Trello` `Postman` `Tizen Studio` `Xcode`

---

## 🌱 Ce que je recherche

Je recherche des missions ou projets où je peux apporter une **véritable valeur QA** :
- Mise en place ou renforcement d'une stratégie d'automatisation des tests
- Intégration de pipelines de tests dans des workflows CI/CD
- Contribution full-stack sur des projets React / Node.js

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MouramChafik&show_icons=true&theme=gruvbox&include_all_commits=true&rank_icon=github" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MouramChafik&layout=compact&langs_count=6&theme=gruvbox&card_width=320" />
</p>

---

## 🧩 Projets récents

| Projet | Aperçu |
|--------|--------|
| [Kids Rules Dashboard](https://kidsrules1.netlify.app/dashboard) | [![Kids Rules](https://github.com/user-attachments/assets/527a2453-d9b4-48e5-a083-2882f75fcb88)](https://kidsrules1.netlify.app/dashboard) |
| [Cineflix Films](https://cineflix-films.netlify.app) | [![Cineflix](https://github.com/user-attachments/assets/da85312d-d9af-4a2c-a313-9c3e00baaa8f)](https://cineflix-films.netlify.app) |
| [Quiz Movies App](https://quizmovies.netlify.app) | [![Quiz Movies](https://github.com/user-attachments/assets/ca6d2725-d8d0-4e19-b5a2-9eb455636ee0)](https://quizmovies.netlify.app) |
| [Task Manager App](https://chafik-taskmanager.netlify.app) | [![Task Manager](https://github.com/user-attachments/assets/84367dc7-92d1-40f4-8218-c21638362717)](https://chafik-taskmanager.netlify.app) |
| [HEARTHAND App](https://hearthand.netlify.app) | [![HEARTHAND](https://github.com/user-attachments/assets/16f888dc-0824-41ce-80b9-ecc4afa81955)](https://hearthand.netlify.app) |
| [Alpha Kids App](https://alphakids.netlify.app) | [![Alpha Kids](https://github.com/user-attachments/assets/ab7177e9-42a3-4119-948b-598ed1bdc762)](https://alphakids.netlify.app) |
| [Muslim Prayer App](https://muslimprayer.netlify.app) | [![Prayer App](https://github.com/user-attachments/assets/29a209b1-bb17-46dd-a658-e56a90eee7e5)](https://muslimprayer.netlify.app) |
| [Soins App](https://soinsapp.netlify.app) | [![Soins App](https://github.com/user-attachments/assets/d448b34f-77aa-4be8-a7b3-cfd79be99d10)](https://soinsapp.netlify.app) |
| [Kids Lyon](https://kidslyon.netlify.app) | [![Kids Lyon](https://github.com/user-attachments/assets/a038fbf5-987d-4c50-b573-fd62fcdbba5d)](https://kidslyon.netlify.app) |

---

## 📫 Contact

<p align="center">
  <a href="mailto:mouram.chafik@gmail.com">✉️ mouram.chafik@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/chafik-mouram/">💼 LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://mouram.netlify.app">🌐 Portfolio</a>
</p>
