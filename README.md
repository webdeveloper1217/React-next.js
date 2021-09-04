<h1 align="center">Ecommerce made with Next.js</h1>

<p align="center">	
   <a href="https://www.linkedin.com/in/rafael-goulartb/">
      <img alt="Rafael Goulart" src="https://img.shields.io/badge/-RafaelGoulartB-03B0E8?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <a href="https://github.com/RafaelGoulartB/next-ecommerce#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-03B0E8.svg" target="_blank" />
  </a>
  <a href="https://github.com/RafaelGoulartB/next-ecommerce/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-03B0E8.svg" target="_blank" />
  </a>
  <a href="https://github.com/RafaelGoulartB/next-ecommerce/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-03B0E8.svg" target="_blank" />
  </a>
  <img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/RafaelGoulartB/next-ecommerce?color=03B0E8" />
  <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/RafaelGoulartB/next-ecommerce?color=03B0E8" />
  <img alt="" src="https://img.shields.io/github/repo-size/RafaelGoulartB/next-ecommerce?color=03B0E8" />
</p>

> This project was made to show a full ecommerce plataform made with Next.js and Nextjs Serverless functions to build the backend, using Apollo Server and Apollo Client to GraphQL.


<br />
<div align="center">
  <img src="https://github.com/RafaelGoulartB/Ecommerce-Quantum/blob/master/Ecommerce.jpg" width="720">
</div>

- Authentication with Cookies Sessions.
- Reset Password using email
- List Products
- Filter products by Category
- Sort list of products
- Live search
- Add products to Wishlist
- Add products to Cart
- Checkout page
- Payment with Paypal
- Review Products
  
# :construction_worker: How to run
**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then:**

### Rename env file
Rename `.env.local-exemple` to `.env.local`
### Install Dependencies
```bash
yarn install
```
### Set up database
```bash
# Create DB using migrations
yarn knex:migrate

# Run seeds to populate database
yarn knex:seed 
```
### Run Aplication
```bash 
yarn dev 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
<br>
<br>
Open [http://localhost:3000/api/graphql](http://localhost:3000/api/graphql) with your browser to run queries or to see docs of API.


