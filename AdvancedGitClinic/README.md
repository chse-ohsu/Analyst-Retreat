# Advanced git clinic

1. Helpful reminders
1. Reversing edits
1. Branching what-if scenarios
1. Searching commits 
1. Working in a team
1. Archive a project


# Helpful reminders

**What is SourceTree?**

* [SourceTree](http://www.sourcetreeapp.com/) is a front-end GUI to git
* An analogy... SourceTree:git :: Chrome:internet
* There are other GUIs to git
    * Just like there are other browsers for the internet
    * SourceTree is (in my opinion) the easiest to work with
* Integrates nicely with GitHub

**What is git?**

* [git](http://git-scm.com/) is a version control system
* git repositories can exist
    * Privately, behind protected firewalls
    * Publicly, hosted in the cloud (e.g. GitHub)
    
**What is GitHub?**

* [GitHub](https://github.com) is a public code repository
* GitHub is not git
    * An analogy... GitHub.com:git :: Amazon.com:internet

There's a really nice, new, cross-platform git GUI client: [GitKraken](https://www.gitkraken.com/).
Not as many features.
But less confusing GUI.
Might be a good alternative if [SourceTree](http://www.sourcetreeapp.com/) is overwhleming.


# Reversing edits

A.k.a. **Super Undo Time Machine**

See [How to undo (almost) anything with Git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git).

1. Edit [`TheMerryAdventuresOfRobinHood.txt`](TheMerryAdventuresOfRobinHood.txt)
    1. Change the title
    1. Globally replace `Sheriff of Nottingham` to `Sheriff of Hazzard County`
    1. Globally replace `Maid Marian` to `Xena, Princess Warrior`
1. `revert` a pushed change
1. `amend` a commit message
1. Undo local changes
1. Reset local changes
1. Redo an undo (must be done in a terminal window)


# Branching what-if scenarios

Why branch?
It's a natural way to explore.

1. Edit [`DistanceBtwnZipCodes.R`](DistanceBtwnZipCodes.R)
1. Add code to output `table` to CSV
1. Add zip code `97215`
1. Source zip codes from [RUCA](https://github.com/chse-ohsu/PublicUseData/tree/master/RUCA)
1. Create a branch to get distances between Portland zip codes, `972[0-9]{2}`
1. Create a 2nd branch to get distances between Los Angeles zip codes, `900[0-9]{2}`
1. Create a 3rd branch to get distances between Portland and Los Angeles zip codes, `97[02][0-9]{2}`
1. Checkout `master`
1. Get distances between all zip codes


# Searching commits


# Working in a team


# Archive a project

Why archive?
To bundle all project code, notes, tables, figures, etc., for a deliverable (e.g., paper submission).
