# Git for dream making
# Collective Creativity

  * Forked from gitea (gitea.io) but with DreamGit flavor.
  * A distributed version control system, like git, but build for collaborating works between artist/illustrators.
  * Simplify the traditional git workflow, with consideration for non-programmers.
  * New terminology for commands, more intuitive.
  * More emphasis on web-base operation, as oppose to command-line operation.
  * Better large file / binary file handling. 

## I have this crazy idea:

  A 'GIT' like distributed version-control system, but designed for coordinating work among creators, enable collaborative open source creative projects.

### OK, just to prove I'm not THAT crazy, let me list out what I think why this is so difficult:

  1. Unlike git for open source codes, where the difference between good and bad is usually pretty clear, thus contributors can eventually reach consensus, creative project, in its very own nature, is subjective. How do you unite people?
  Basically, there are a thousand Hamlets in a thousand people's eyes.

  2. Code, in its own native format (pre-compiled that is), is designed to be readable, a .py file can be distributed, viewed, edited and commented entirely in its own format, thus making a centralized web interface easy to build. Arts, varies hugely between different media, a manga could have a lot images, svg and text, a visual art piece could be one big .psd file. Those files are not readable in its own native format, very hard to do git like version control, and even harder to view, share and comment on a web interface.

  3. Artists are not nerds like us coders, even I find the git system unintuitive at times, let alone people with zero programming knowledge. How do we make an artistic git that is not only intuitive for pro artists, but EVERYONE?

### So, this is what I am proposing:

  1. The fundamental principle, regarding how to settle differences regarding differences between creative views, shouldn't be focused on what is 'good or bad', but:
      Share, Parallelism, Acceptance and Freedom.
    (I know this sounds hippie, but more details in SPAFprinciple.md)

  2. Limit the scope of this initial project, start by designing the system to focus on graphics projects (manga, illustration book, comics etc), with strong support for vector and raster files.

  3. Unlike git (a lightweight command line tool), this project should be built around a robust and intuitive graphical front-end (js), with a fast and scalable back-end (golang).

HW
