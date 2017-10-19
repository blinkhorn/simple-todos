# Meteor

# Why I chose Meteor?

I chose to learn Meteor on this "Teach Yourself" lesson because it seems to be
a simple way to deploy mobile + web apps. I was first made aware of it by
the suggested topics in today's lesson plan.

# What problem does it solve?

It makes it easier for developer to quickly push apps to Android, iOS, and a
Web app. From Wikipedia: "Meteor allows for rapid prototyping and produces
cross-platform (Android, iOS, Web) code. It integrates with MongoDB and uses the
Distributed Data Protocol and a publish–subscribe pattern to automatically
propagate data changes to clients without requiring the developer to write any
synchronization code. On the client, Meteor can be used with its own Blaze
templating engine, as well as with the Angular framework or React library."

# Why does one use it?

To easily deploy apps to multiple mediums. Alternatively you can deploy your
app to each system separately. I'm currently not aware of similar ways to do
this.

# What is the history of this technology?

Originally started in December 2011 under the name Skybreak. From Wikipedia:
"Meteor is developed by the Meteor Development Group. The startup was incubated
by Y Combinator and received $11.2M in funding from Andreessen Horowitz in
July 2012. Meteor raised an additional $20M in Series B funding from Matrix
Partners, Andreessen Horowitz and Trinity Ventures. It intends to become
profitable by offering Galaxy, an enterprise-grade hosting environment for
Meteor applications."

# What is your opinion on the technology after having built something with it?

It seems to be very useful given what it can do (deploy easily to multiple
systems), but it seems relatively slow when exporting the app.

# What are the biggest conceptual hurdles (if any) you encountered when
# researching this?

I did not encounter any conceptual hurdles.

# What resources do you recommend for interested students?

[The Meteor tutorials](https://www.meteor.com/tutorials)

# What are 3 interview questions one might be asked about this technology?

1. What is Meteor?
2. Have you built anything in Meteor? If so, may I see what you built?
3. What is the general file structure of a Meteor project?

# How to run and use my example:

1. If you don't have Meteor, install it:
```bash
$ curl https://install.meteor.com/ | sh
```
2. Clone the project down.
3. CD into the project
4. Run:
```bash
$ meteor
```
in one tab and run:
```bash
$ meteor mongo
```
in another tab.
5. Go to the specified port in your browser — you should see the app there.
