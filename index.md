# Stability Markers

Stability Markers indicate how mature a project is.

> Projects naturally go through stages. Some are experimental and in flux.
> Others enjoy steady contribution toward a clear roadmap. Still others are
> basically finished, needing only the occasional fix. And, as is the nature of
> our business, sometimes software becomes obsolete.

Repositories on GitHub and other places use Stability Markers to let
users know what to expect from a project. Early adopters may be excited
to find new **experimental** projects, while developers concerned with
production usage might instead look for **active** or **sustained**
projects. Finally, it is the nature of software to change, and sometimes
projects become **unsupported**. The Stability Markers project helps
you inform your users which of these is the case.

## Using Stability Markers

Using a stability marker is as simple as including the relevant badge on
your site. We strongly recommend linking the badge back to our
description so that users unfamiliar with Stability Markers can learn
more.

## Marker

In most cases, projects move from one stability marker to the next, in
sequence. Below, they are presented in the order of the presumed ideal
lifecycle.

### Experimental

Not ready for prime-time. Code has not stabilized.
[Full description](experimental.html)

[![Stability: Experimental](https://masterminds.github.io/stability/experimental.svg)](https://masterminds.github.io/stability/experimental.html)

```markdown
[![Stability: Experimental](https://masterminds.github.io/stability/experimental.svg)](https://masterminds.github.io/stability/experimental.html)
```

### Active

At least one stable release, active contributors, and major
future releases. [Full description](active.html)

[![Stability: Active](https://masterminds.github.io/stability/active.svg)](https://masterminds.github.io/stability/active.html)

```markdown
[![Stability: Active](https://masterminds.github.io/stability/active.svg)](https://masterminds.github.io/stability/active.html)
```

### Sustained

At least one stable release, considered "feature complete", and
future releases focus on stability and security. [Full description](sustained.html)

[![Stability: Sustained](https://masterminds.github.io/stability/sustained.svg)](https://masterminds.github.io/stability/sustained.html)

```markdown
[![Stability: Sustained](https://masterminds.github.io/stability/sustained.svg)](https://masterminds.github.io/stability/sustained.html)
```

### Maintenance

At least one stable release. Product is considered mature, and
maintainers only make bug fixes.
[Full description](maintenance.html)

[![Stability: Maintenance](https://masterminds.github.io/stability/maintenance.svg)](https://masterminds.github.io/stability/maintenance.html)

```markdown
[![Stability: Maintenance](https://masterminds.github.io/stability/maintenance.svg)](https://masterminds.github.io/stability/maintenance.html)
```

### Unsupported

The project is no longer maintained. This does not mean there is
anything wrong with the project; it reflects the state of activity.
[Full description](unsupported.html)

[![Stability: Unsupported](https://masterminds.github.io/stability/unsupported.svg)](https://masterminds.github.io/stability/unsupported.html)

```markdown
[![Stability: Unsupported](https://masterminds.github.io/stability/unsupported.svg)](https://masterminds.github.io/stability/unsupported.html)
```

## Is It About Software or Community?

Stability Markers are intended to indicate the maturity of a _project_, not
of the code itself. (SemVer is for code stability.) Stability Markers
are intended to answer questions like:

- Is this project actively maintained?
- How often can I expect a release from this project?
- Should I expect a quick turn-around on a bug report?
- Am I better off forking the project or contributing to it?
- Is this a project that I might be able to join as a maintainer?

Because of the nature of software, many of these questions are tied to
the maturity of the code. Stability Markers, for example, require at
least one stable release before a project can exit `experimental`.

## Who Enforces These Guidelines?

Stability Markers are self-governed: Project owners self-assign the Stability
Marker they believe best describes their project.

## Star Us!

If you use Stability Markers for your project(s), we humbly request that
you star this project [on GitHub](https://github.com/Masterminds/stability)
so that we have at least a basic metric for how many people find this
project useful.
