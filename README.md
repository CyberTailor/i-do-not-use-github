# I Do Not Use GitHub

While you may see some commits of mine for projects I wanted to contribute to,
_I do not use GitHub for personal projects_.

**My projects can be found at https://git.sysrq.in**,
with a mirror of some of them on this site and at https://git.sr.ht/~cyber.


## Why Not GitHub?

Primarily because GitHub requires users to run
[non-free JavaScript](https://www.gnu.org/philosophy/javascript-trap.en.html),
which is by the way
[broken in some browsers](https://github.com/JustOff/github-wc-polyfill/issues/43),
to use all features of the website.
Not only will I not do this,
but I don't want to direct users to GitHub either,
because doing so is asking them to run non-free software.

For more information, see:

* https://mikegerwitz.com/about/githubbub
* https://sanctum.geek.nz/why-not-github.html

I've come to be displeased with GitHub even more when it started to push its Copilot AI "features" into everyone's faces.


## Why GitLab?

GitLab
[has committed to licensing all client-side JavaScript under a free license](https://about.gitlab.com/2015/05/20/gitlab-gitorious-free-software/).
Not only does this mean that I can use GitLab without running non-free software,
but it also means that I am not asking others to visit a website that causes them to run non-free software.

GitLab also releases their Community Edition as free software,
which means that users are free to self-host using free software if they so choose.


## Why not GitLab?

The gitlab.com website is run by proprietary server software.
Also,
GitLab is not accessible without JavaScript enabled and hostile to Tor users.

[SourceHut](https://sourcehut.org)
is 100% FOSS and all of its features work without JavaScript.

If fancy features that SourceHut lacks are needed,
[Forgejo](https://forgejo.org)
is a good alternative too.


## How do I send you PRs?

Pull requests (PRs) are not the only way to send changes to others.
In fact,
it's not even a feature of Git itself.

You have a few options:

- If your repository is published somewhere (be it this site or elsewhere),
  I can add it as a remote (using
  `git remote add`
  ) and merge your changes.
  Use
  `git request-pull`
  to create such email automatically.
- Email the patches to me.
  You can prepare them using
  `git send-email`.
- If the repository is on a libre source forge,
  I'll collaborate with you there.
- [Get in touch with me](mailto:cyber@sysrq.in)
  and I'll help you out.

## License

This document is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license (CC BY-SA 4.0).
