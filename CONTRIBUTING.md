## Commit Guidelines

> NOTE: subject to change

- At Splitscale, we use 50/72 standard for commits. 50 characters max
  for the title (excluding module prefix), an empty line, and then a
  full description of the commit, wrapped to 72 columns max. See this
  link for more information: http://chris.beams.io/posts/git-commit/

- Make sure commit titles are always in present tense, and are not
  followed by punctuation.

### Write a title summarizing what this commit does.

Prefix each commit's titles with the module name, followed by a colon
and a space (unless modifying a file in the base directory). After
that, the first word should be capitalized.

_So for example, if you are modifying the `models` module:_

```
models: Add item card
```

### For the body, describe a short yet concise of what Problem, Task, or Reason for Commit.

> Describe the purpose, such as a goal, or use case, or user story, etc.

```
<!-- in this case we used a user story -->

Description:
We do not have a card class for items
We need this to display item info in main menu
```

### What should be the expected behavior of this commit?

> Describe what this commit can do or should do etc.

```
Expected behavior:
Should be able to display items in the
home page.
```

### Tags, class names, etc.

> list down some notable tags

```
Tags:
- ItemCard
- Card
- DisplayableObject
```

### Trailers

Trailers suitable for tracking and also for `git interpret-trailers`.

> Example of "See:" trailers that mean "see this additional information"
> and links to relevant web pages, issue trackers, blog posts, etc.:

```
See: https://example.com/
See: Issue #123 <https://example.com/issue/123>
```

## Full example

```
models: Add item card

Description:
We do not have card for items
We need this to display item info in main menu

Expected behavior:
Should be able to display items in the
home page.

Tags:
- ItemCard
- Card
- DisplayableObject

See: Issue #23
```

---

**If you still need examples, please view the commit history.** :eyes:
