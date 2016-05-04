# DBC Open Source Talk Notes

### Why Open Source

* __Giving back:__ People take the time to create amazing pieces of software that they give to the world for free. The least you could do to thank them is to help them in their endeavors.

* __Learning:__ Working on a diversity of projects means you get the opportunity to learn a bunch of stuff from a ton of really great people. Normal 9-5 work is typically much more narrow in scope, but with OSS you can get an incredible breadth of experience.

* __Community:__ OSS is a massive community that brings together people from all over the world, with an incredible variety of experiences and beliefs, to build great stuff. If you want to be part of a broader community of developers, this is a great way to do so!

### Open Source Rules

__RULE 1:__ If you find something wrong with a piece of open source software, fix it.

__RULE 2:__ In the event you are unable to adhere to rule 1, tell a maintainer about the problem you found in a polite fashion (and preferably with a detailed example of how to recreate the issue you found).

__RULE 3:__ If you are unable to adhere to either rule 1 or rule 2, do nothing. It's not a good use of anyone's time to be complaining about stuff on the internet. There's enough of that already.

### How to find a good project to work on (for beginners)

* __Find a project in the _sweet spot_ of size and complexity.__ Your first OSS commit probably won't be to Rails or Node, but that doesn't mean that your first commit should be to a project that isn't widely used and isn't well maintained. Try to find a project that is well used and maintained enough so that it has an active community around it, but not so big that it's hard to get anything done. I recommend projects that have between 300-600 stars on GitHub (which is a totally random and arbitrary number, but seems to work for me).

* __Look at the recent activity of a project to gauge maintainer engagement.__ Is the last merged PR from 2015 or before? Are there issues open from six months ago that don't have any responses by a project maintainer? Then this project may not be the best place to start. Look for somewhere where the maintainers are active, kind, and helpful.

* __Look for projects with helpful tags on issues.__ There are some projects out there that tag issues with various pieces of metadata to help filter them. Some of these projects include tags like `documentation` or `easy` or `beginner` - these are great places to start!

* __Find a project where you'll feel welcome.__ If you feel like it will help you confidently be part of a project's community, look for a project with a good code of conduct. This isn't really important to everyone, but it's very important to some, so it's something to consider.

* __Think about what you want to get out of it.__ Like we mentioned before, there are various reasons people contribute to open source. If you're doing it as a learning opportunity, then looking for a project with extra helpful maintainers is a good call. If you're doing it to give back, then you might want to contribute to a project that you use all the time and love having around.

* __Find some really great people and target projects they manage.__ Sometimes just searching through GitHub for repositories can be a bit of a scattershot approach to finding a good project. If you know of some really great maintainers, you can narrow your search down to projects that they own.

### Where to start as a contributor

#### Documentation

Everybody says it, and everyone thinks its no fun, but documentation is a really important part of OSS, and its one place where beginners are actually more able to do a good job than those who are more experienced with the project. Beginners are the primary audience for documentation, so as a beginner your input has a lot of value. So, if you go to the README for a project and you find the documentation lacking or confusing, submit a PR that enhances the docs!

There are also opportunities for documenting code inline, which some projects do and some projects don't do. One thing I like to do is to go through the recently merged PRs for new features and see if I can find any that were merged without documentation and then submit the PR for the documentation for that feature. This is great because you only need to be familiar with the code that's in the PR and you don't necessarily need to get up to speed with everything that the library is doing.

#### Refactoring

If you're not familiar with Code Climate, then it would be good to get familiar. This is a great tool that you can leverage for _any_ open source project to identify areas of the codebase that need some attention - you don't need to be the project owner to set it up!

Refactoring PRs can be tricky because certain projects have rules about what they consider a 'refactor' versus just a different style of solving a problem, but they can frequently be easy to find and easy to approach as a beginner in a project. The thing to watch out for here, though, is that you're going to potentially get a lot of opinions on if your refactor is the 'right' way to refactor something. These kinds of PRs can be tricky not technically, but interpersonally.

#### Bug fixes

As a beginner, bug fixes are harder than refactoring but easier than adding new features, so they can be good places to start if the project you want to contribute to doesn't accept a lot of refactoring PRs. The more detailed and exact the description of the bug, the better, so look for issues that are open with really good bug reports as a place to start.

They're easier than a new feature because typically there's an obvious place to start (where the bug occurs), and then you can weave your way through the code that you need to understand in order to fix it. Again, you shouldn't need to have an overall understanding of the project before you start, and in fixing a bug you can learn a lot about a project that will benefit you later on as you make more contributions.
