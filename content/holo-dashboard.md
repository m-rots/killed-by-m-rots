+++
title = "Holo Dashboard"
date = 2019-10-20

[extra]
killed = "October 2019"
+++

By far the most ambitious project, Holo was aiming to replace PlexGuide and CloudBox with a magical solution. The idea began to take shape in the summer of 2018. PhysK, The Creator and I brainstormed for multiple months how we could create a dashboard which could install an entire media server in a matter of seconds. It was my first (big) coding project and none of us had any experience creating anything like it.

The initial version was created with JavaScript (NodeJS) and was aiming for a server-client model. We created a GraphQL API and a couple of things were working. However, while figuring out how we were going to handle cloud storage (Google Drive), I lost myself in creating Dash. When I learned that a cloud-model was not the solution for Dash, I imagined it would not be the solution for Holo either.

A couple of months later, PhysK contacted me that he had created a new version of the Holo Dashboard which did not rely on cloud infrastructure. I immediately jumped onboard and threw in all my  newly acquired TypeScript knowledge to make the developer experience splendid with auto-complete for various applications and backends. However, I had this opinionated idea of using a self-hosted DNS server to manage wildcard SSL certificates. While the prototype worked initially, it stopped working on my machine a couple of weeks later. I lost interest and the second iteration of the Holo Dashboard died with it.

<!-- more -->