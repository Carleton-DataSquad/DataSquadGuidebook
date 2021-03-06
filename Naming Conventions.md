# Bitbucket and Github:
*inspired by: https://github.com/agis-/git-style-guide#commits and http://stackoverflow.com/questions/273695/git-branch-naming-best-practices*

## General Rules:
* avoid long, descriptive names
* with the exception of dates, do not just use numbers

## Project (Folders):

*Naming*: Client-ProjectName-Time

*Ex*: PLacke-GuideBook-2016, ChildV-SomeProject-2017

If you are creating folders for the same projects across multiple platforms (Github, Google Drive, etc.), be sure to keep the folder name the same for all projects.

## Branches:

* master = main branch, should only have working code
* devel/project-name = all branches from main are considered in development. Specify branches by project names

## Commit Messages:
(see https://chris.beams.io/posts/git-commit/)

### *Generale Rules:*
* Separate subject from body with a blank line
* Limit the subject line to 50 characters
* Capitalize the subject line
* Do not end the subject line with a period
* Use the imperative mood in the subject line
* Wrap the body at 72 characters
* Use the body to explain what and why vs. how

### *Naming*

Subject line: 
A properly formed Git commit subject line should always be able to complete the following sentence:

    "If applied, this commit will ~~~your subject line here~~~"

Message Template:

    Short (50 chars or less) summary of changes

    More detailed explanatory text, if necessary.  Wrap it to
    about 72 characters or so.  In some contexts, the first
    line is treated as the subject of an email and the rest of
    the text as the body.  The blank line separating the
    summary from the body is critical (unless you omit the body
    entirely); tools like rebase can get confused if you run
    the two together.

    Further paragraphs come after blank lines.

    - Bullet points are okay, too

    - Typically a hyphen or asterisk is used for the bullet,
      preceded by a single space, with blank lines in
      between, but conventions vary here