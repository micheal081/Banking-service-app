<h1>
Full Stack Web Application similar to financial software that is used in professional banking institutions.
</h1>

The banking service application is a robust platform built with TypeScript, Node.js, and Nest.js, incorporating solid design principles like SOLID, DRY, and KISS. It employs double-entry bookkeeping for accurate account balance calculation and supports multiple currencies via API integration. The software ensures seamless user experience across browsers and devices with Progressive Web App (PWA) support and adheres to GDPR regulations with Google Analytics and Cookie Consent. Powered by PostgreSQL, it offers reliable data management, while clear documentation through Swagger enhances accessibility. The system requires Node.js, yarn, and PostgreSQL for installation and is licensed under MIT.

</div>

- The current account balance is calculated based on the SQL operation (**Double-entry bookkeeping**)
- Support for **multiple currencies** with the current rate supplied from an external server via **API**
- Application programmed according to the correct design patterns and principle, i.e. **SOLID**, **DRY** and **KISS**
- Software supports **PWA**, it is adapted to all modern browsers and mobile devices (RWD)
- Implementation of **Google Analytics** along with the Cookie Consent according to the **GDPR**

<hr>

<hr>

<dl>
  <h3>Backend technologies stack</h3>
  <dd><a href="https://github.com/microsoft/TypeScript">TypeScript</a>, <a href="https://github.com/nodejs/node">Node.js</a>, <a href="https://github.com/nestjs/nest">Nest.js</a>, REST API, PostgreSQL and Swagger Documentation</dd>
</dl>

<hr>

<h4>System requirements</h4>

- [**Node.js** v12.18+](https://nodejs.org/en/)
- [**yarn** v1.22+](https://classic.yarnpkg.com/en/)
- [**PostgreSQL** v10.12+](https://www.postgresql.org/)

<h4>Installation</h4>

```bash
# 1. Install the required dependencies
yarn

# 2. Rename the .env.example filename to .env and set your local variables
mv .env.example .env

# 3. Start the server with the backend application
yarn start
```

<h4>License</h4>
This project is licensed under the MIT license.
