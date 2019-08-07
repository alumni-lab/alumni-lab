- Virtual Boxes
  - Vagrant Box
      The goal of Vagrant is to make it simple to create a local development environment so that you’d never want to do it another way again.
      This power is amazing and applicable for freelancers who work on many different projects—or companies that need to onboard new members of a team as quickly as possible. With Vagrant, the configuration of development and the production environment can be mirrored as closely as possible. Errors like “works on my machine” become a thing of the past.
- Why Build A Box?
There are a bunch of amazing boxes out there available on sites like vagrentbox.es and vagrantcloud.com so why would you want to build your own box?

Maybe you want to add a few extra things to your base (a runtime or two like Julia, Erlang, JVM or Python, etc.) then start this as your new “base”.
Maybe you want your box to have more ram or you need your boxes to more closely mirror production and you are building a ram enriched, multiple server cluster with multiple provisioners, we get it… you’ve got a mountain to climb, you just need your gear.

- Rebuild the LHL vagrant box