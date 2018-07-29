---
category: blog
---

Did a lot of travelling in June, so I couldn't do much, but July was a huge success. I'm quite excited about things.

* I've moved to a [GraphQL](https://graphql.org/) structure. This will reduce latency and network transfer volume.
* Many types are now exposed, including user information, games data and metadata, and challenges.
* I'm slowly adding the mutators. You can currently create/modify profiles and issue and respond to challenges.
* There's some back end stuff happening too (game pinging and status updates).

Because of some limitations with AWS around VPCs, and my commitment to [an open games API](https://github.com/AbstractPlay/abstractplay.github.io/wiki/api.thirdparty) (so that others can code games independently of my code base), some database writes will be asynchronous. We'll have to wait and see how that affects the front end.

I'm currently blocked by a known bug in Entity Framework Core ([issue #12749](https://github.com/aspnet/EntityFrameworkCore/issues/12749)), but there are other things I can do until a fix or workaround shows up.

Forward!