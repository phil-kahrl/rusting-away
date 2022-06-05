# Rusting Away

This is my blog on my experience learning Rust and (hopefully) using it to build applications.

## Why am I doing this?

There are a lot of good reason to learn a new language and build new skills but I'm lazy so good reasons weren't enough.  The straw that broke the camel's back came from my frustration with the npm ecosystem and the libraries and tooling therein.

I wanted to build a new version of an web application that I maintain for personal and family use. The most recent version was built 4 years ago using what was considered state-of-the-art at the time with the latest libraries from the React team and material UI.  After not working on the project for a couple of years, I tried to install and build with npm and, of course, the build was broken in a hundered different ways because dependencies have moved on and nothing is backwards-compatible, so now I would need countless hours of my precious spare time to update dependencies, and probably fix a lot of existing code broken by updated dependencies.

I decided instead to start fresh with the latest and greatest and build from the ground-up with the latest versions of everything and build something solid and extensible from the ground-up.

I didn't get very far.  While adding the last library that I really needed for the project, I found that it wasn't compatible with latest version of webpack, so now I would need to change the webpack version and all it's dependencies, so I'm back in dependency purgatory.

So one day I read an article about writing Rust to WASM, and I think maybe I should just try that.  It will take a while, but I'll learn something along the way, and that will be a better use of my time than constantly fixing npm builds in hopes that I will have some time left over to actually write application code.