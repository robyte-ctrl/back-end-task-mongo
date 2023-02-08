![Logo](https://bend.md/images/5e8730206d541c6309354d3e_image%20(4).png)

# Back-End Task

**Create a [node.js](https://nodejs.org) [web service](https://en.wikipedia.org/wiki/Web_service) for a blogging app with a [RESTful](https://en.wikipedia.org/wiki/Representational_state_transferj) api that works with [JSON](https://www.json.org) data using [express](https://expressjs.com/) or [nest](https://nestjs.com/) as a framework and [mongo](https://www.mongodb.com) or [postgres](https://www.postgresql.org/) as a database.**

Blogging can involve many things so, to keep this simple, the main focus is on **users** and **posts** created by **users**. The structures for these entities are irrelevant as long as they're usable and aren't hard to understand, in other words, you can define **users** and **posts** however you want but make sure that it won't be too hard to understand how each of their properties contribute to form a blogging app that respects the requirements enumerated below. The same goes for endpoints.

### Requirements:

1. [typescript](https://www.typescriptlang.org/)
1. RESTfull web service working with JSON data in node.js using nest/express and mongo/postgres
1. two types of **users**: **bloggers** and **admins**
1. authentication with name/email and password, with sign-up and sign-in for **bloggers**, but only sign-in for **admins**
1. **bloggers** can create **posts**
1. **bloggers** can update and remove their **posts**
1. **bloggers** can publish and hide their **posts**
1. **bloggers** can see their **posts** whether they're public or hidden
1. **bloggers** can see **posts** of other **bloggers** as long as they're public
1. **admins** can do everything **bloggers** can do
1. **admins** can remove any public **post**

Good practices and readable code are very welcome.

If you think that something is missing, feel free to contact us.
