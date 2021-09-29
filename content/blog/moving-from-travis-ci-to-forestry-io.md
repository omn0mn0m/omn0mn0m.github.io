+++
date = "2019-07-09T16:00:00+00:00"
title = "Moving from Travis CI to Forestry.io"

+++
This will be just a quick little update. As of a few minutes ago, my personal website is no longer being built using Travis CI. While I love Travis CI for continuous integration for almost all of my projects, I felt that the hoops that had to be jumped through to publish new blog posts were just too many (mainly related to creating RSA keys).

I have since moved to Forestry.io, which is a free headless CMS meant for static site generators. As my website is currently using Hugo, this seemed to be a no-brainer. I'll update this post with how it goes once I do my first deploy...

### Post-Move Update

I have officially moved to Forestry and used its deploy system to update my website and post a blog post. I can confirm that everything works, and it feels very easy to use. To avoid the effort to make Travis CI work for pushing to GitHub Pages for static site generators (other than Jekyll), I highly recommend moving to Forestry.io.

Now to wait a few years for me to declare a new recommendation...