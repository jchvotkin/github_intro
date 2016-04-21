# Intro to Git & GitHub

### What is Git, and What is GitHub?

Git is an open-source application written to help teams of people 
collaborate on projects. Specifically, the teams are meant to be highly
*distributed*, and the projects must be represented by files on a
computer, ideally *text files*.

GitHub is a company, and the name of suite of products that it sells.
GitHub offers three products to its users:

1.  a **cloud storage service** for Git projects;
2.  a web application that is fully integrated with the cloud service,
    offers extra functionality alongside Git, and a graphical, web-based
    interface to using it;
3.  a series of downloadable, "native" applications for desktop/laptop 
    users (no mobile or tablet "apps" yet) that integrate with the
    cloud service and offer a graphic interface (GUI) instead of the
    default command-line interface (CLI) for Git.

There is a fourth "product" from GitHub, but it is an open-source tool:
the Atom text editor.

### When Do I Use Git?

Git has a pretty specific use-case that it was written for: a *very*
large, *very* complex, *software project*, that is run by a "benevolent
dictator" (ie, managed democracy)

There are other tools that allow project collaboration! For example,
we often use cloud document services like Microsoft Office or 
Google Docs. There are tools for planning or ideation that are not
text-based, like Doodle. There are also bigger tools like Basecamp, or
tools that are specific to project management, like Trello. There are 
other, more complex tools and processes that we can use to share work, 
as well.

Finally, there are many software collaboration tools, like Mercurial,
and CVS. Git is realtively new: most teams never touched it until the 
last 5 years!

##### So when do we use Git?

1.  When you are working on text files.
2.  When you have a team that is not able to meet face-to-face.
3.  When you want to have a way to suggest and discuss changes before
    accepting them.
4.  When you care about the *history* of a project, and may want to
    remove specific changes from history.

##### When do we not use Git?

1.  When you are not working on text files. The end.
2.  When your project is simple, and the team is small.
3.  When no one knows how to use Git!
4.  When you want to keep very tight control over changes.

### So, Git? What is it, again?

Git has some pretty specific vocabulary associated with it. Let's
dig in to Git by talking about what it can do:

- **Repository**, ie **repo**,
- **branch**,
- **commit**,
- **tracked**, **staged**,
- **merge** and **rebase**, ie ***synchronize***,
- **remotes**, and **push**/**pull**,
- *workflow*.

