<p align="center">
  <img src="img.shields.io/badge/node_logo.svg" width="200" alt="Node Logo" /></a>
</p>

<p align="center">
		<em>Developed with the software and tools below.</em>
</p>

<p align="center">
    <img src="img.shields.io/badge/nodejs.svg?style=flat&logo=nodejs&logoColor=white" alt="Node">
    <img src="img.shields.io/badge/vitest.svg?style=flat&logo=vitest&logoColor=white" alt="Vitest">
</p>

## 📝 Overview

Software Design refers to the intentional and organized creation of software systems with the goal of satisfying specific user needs, meeting quality and performance requirements, and ensuring code maintainability.

Domain Driven Design (DDD) is a software design approach that focuses on modeling the application domain to represent real-world business rules and concepts.

The main difference is that Software Design focuses on the overall architecture of the system, while DDD emphasizes domain modeling.

Translated into PT-BR, DDD means Design Dirigido à Domínio.

---

## 📦️ Main concepts covered

<h4><code>Domain Experts</code> are people who have knowledge of the process or procedure of something (This stage is based on conversation using a ubiquitous language)</h4>
<h4><code>Entities</code> represent real-world objects that have an identity and maintain a state that is relevant to the application.</h4>
<h4><code>Use cases</code> dscribe the functionalities (actions) that the software must perform to meet the needs of users or the business.</h4>
<h4><code>Through OOP</code> we can create classes that represent these entities and use cases, making the code more organized and structured.</h4>
<h4><code>The Getters and Setters methods</code> in the application entities allow accessing and modifying the values ​​of their properties in a controlled manner.</h4>
<h4><code>Aggregates</code> organize and maintain the consistency of related objects.</h4>
<h4><code>Watched Lists</code> ithese are lists of objects that are monitored as changes occur in the aggregated objects.</h4>
<h4><code>Domain Events</code>, which is a technique used to deal with communication and actions between domains in software architecture.</h4>

```sh
Subdomains {
    core - what gives money
    Supporting - provides support for the core to work
    generic - you need it but it's not that important
}
```

```sh
Explaining Right and Left: 

Right
UI -> CTRL -> USE CASES -> ENTITES -> USE CASE > Repository -> DATABASE


Left 
UI -> CTRL -> USE CASES <- ENTITES
```

---

## 🧪 Test

As one of the pillars of the application was DDD, no routes were created to ensure that the application would function fully.

To run the tests, just follow the commands below:

> 1. Clone the repository:
>
> ```console
> $ git clone https://github.com/diego64/api-qa-forum
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd api-qa-forum
> ```
>
> 3. Install the dependencies:
> ```console
> $ npm install
> ```
> 4. Run the tests:
> ```console
> $ npm run test
> ```