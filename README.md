# purescript

Exercism problems in PureScript.

## How to contribute

Thank you so much for contributing! :tada:

- [Asking for help](#asking-for-help)
- [How to contribute](#how-to-contribute)
  * [Reporting or fixing bugs](#reporting-or-fixing-bugs)
  * [Reviewing issues and pull requests](#reviewing-issues-and-pull)
  * [Porting exercises](#porting-exercises)
- [Repository structure and conventions](#repository-structure-and-conventions)
- [Writing a pull request](#writing-a-pull-request)


### Asking for help

When in doubt just [open a GitHub issue][new-issue] and ask! In any case,
don't be afraid or shy! We promise to be friendly and as helpful as possible.

[new-issue]: https://github.com/exercism/purescript/issues/new


### How to contribute

As a first step we recommend you read the [contributing guide][cont-guide].

[cont-guide]: https://github.com/exercism/docs/blob/master/contributing-to-language-tracks/README.md

Due to Travis builds taking too long and timing out, the current build plan compiles and runs the tests for all exercises in a single run. This requires the following:

- A master bower is given in `etc/bower.json`. Test scripts assure this one is used when they are run
  * Please only update the master one and then run `bin/update-bower.sh` to sync them up. 
  * After editing `etc/bower.json`, it is advisable to run `bin/check-bower.sh`. This checks for any discrepancies between various bower scripts.
- Make sure exercises have a single module in `examples/src`

See [this PR](https://github.com/exercism/purescript/pull/71) for more details and the background.

#### Reporting or fixing bugs

Typical examples for a bug: A typo, a missing test case, an unclear or
ambiguous problem description.

- If you are unsure whether you have really found a bug [just ask](#asking-for-help).
- To report a bug you can [write an issue][new-issue]
- If you already have a fix for it you may [write a pull request](#writing-a-pull-request).

#### Reviewing issues and pull requests

If you have an opinion or feedback on work currently being done on this track
please do [write a comment][write-comment] for an [issue][issues] or a
[pull request][prs]. Feedback is extremely useful to us.

[write-comment]: https://help.github.com/articles/commenting-on-a-pull-request/
[issues]: https://github.com/exercism/purescript/issue
[prs]: https://github.com/exercism/purescript/pull

Please be detailed and include any links or arguments to support your
opinion.

#### Porting exercises

Here is the [list of missing exercises][missing]. See here for more
information about [porting an exercise][porting]. Of course you can also add a
totally new exercise, but it might be a good idea to first discuss it in one
of [our forums](#asking-for-help).

[missing]: http://exercism.io/languages/purescript/todo
[porting]: https://github.com/exercism/docs/blob/master/contributing-to-language-tracks/README.md#porting-an-exercise-to-another-language-track


### Repository structure and conventions

[Here](https://github.com/exercism/docs/blob/master/contributing-to-language-tracks/README.md#track-anatomy)
is a general description of all the files and directories that are not
explicitly described below.


### Writing a pull request
To fix a bug you should [create a pull request from a fork](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) [here](https://github.com/exercism/purescript/pull). See also [here](https://github.com/exercism/docs/blob/master/contributing-to-language-tracks/README.md#git-basics) for more information.



### Purescript icon
The PureScript logo was created by Gareth Hughes, and is licensed under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
We have adapted it, changing the colour scheme, for use on Exercism.
