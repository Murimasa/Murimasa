# Hi there, I'm Mikhail 👋

### QA Engineer | Expanding into Test Automation (Python & Playwright)

Experienced QA Engineer with a solid background in **Game QA and manual testing**, actively expanding expertise into automated testing, API frameworks, and CI/CD pipelines.

I combine strict testing fundamentals, edge-case analysis, and bug tracking rigor with modern automation practices using **Python**, **Playwright**, **Requests/Pydantic**, **Postman/Newman**, and **GitHub Actions**.

---

### 🛠️ Tech Stack & Tooling

**Core QA & Platforms**  
![Game QA](https://img.shields.io/badge/Domain-Game_QA_%26_Software_Testing-4CAF50?style=flat-square)
![Console & PC](https://img.shields.io/badge/Platforms-PC_%7C_Consoles_%7C_Mobile-555555?style=flat-square)
![Bug Tracking](https://img.shields.io/badge/Process-Bug_Reporting_%26_Verification-FF9800?style=flat-square)

**Test Automation & Programming**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**API Testing & Postman Ecosystem**  
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![REST API](https://img.shields.io/badge/API-RESTful_Microservices-85EA2D?style=flat-square)

**CI/CD, DevOps & Reporting**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Allure](https://img.shields.io/badge/Allure_Report-FFA000?style=flat-square&logo=allure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 🚀 Automation Portfolio Projects

#### ⚙️ [RESTful API Automation Framework (Python)]([https://github.com/Murimasa](https://github.com/Murimasa/python-api-automation-framework))
> Production-ready API testing framework designed for regression and contract testing of RESTful microservices.

* **Architecture:** Custom HTTP Client layer (`core/api_client.py`) encapsulating session management, Bearer authentication, and automatic Allure payload/response attachments.
* **Contract Validation:** Strict schema compliance and payload type enforcement via **Pydantic**.
* **Test Data Management:** Dynamic data factories with **Faker** to prevent collision and preserve isolated state.
* **Performance & Scale:** Multi-threaded parallel execution via `pytest-xdist`, parameterized boundary testing (`@pytest.mark.parametrize`), and automated CI execution in GitHub Actions.

#### 🎭 [Playwright UI Automation Framework](https://github.com/Murimasa/playwright-ui-framework)
> Modular end-to-end UI testing framework built with **Python**, **Playwright**, and **Pytest** implementing the **Page Object Model (POM)**.

* **Target Web App:** [SauceDemo](https://www.saucedemo.com/)
* **Implementation:** Modular Page Object structure, session storage state reuse (`conftest.py`), and web-first auto-wait assertions.
* **Coverage:** Parameterized sorting and authentication errors, cart lifecycle, cancel navigation, and end-to-end checkout.
* **CI/CD & Reporting:** Headless test execution in GitHub Actions, automatic failure screenshots, Playwright trace logs, and interactive Allure reports.

#### 🚀 [Restful Booker API Automation (Newman)](https://github.com/Murimasa/postman-api-automation)
> Headless API regression and data-driven testing framework using **Postman**, **Newman CLI**, and **GitHub Actions**.

* **Target API:** Restful Booker API
* **Implementation:** End-to-end CRUD progression (`POST` -> `GET` -> `PUT` -> `DELETE`) with dynamic token extraction and variable handling.
* **Coverage:** Data-Driven Testing (DDT) using external JSON datasets (`testdata.json`) without commercial platform limits.
* **CI/CD & Reporting:** Automated execution on Ubuntu runner with interactive HTML test dashboard artifacts (`newman-reporter-htmlextra`).

---

### 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)]([https://linkedin.com](https://www.linkedin.com/in/mikhail-tsaryov/))
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](@murimasa)
