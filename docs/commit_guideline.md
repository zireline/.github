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

Describe the purpose, such as a goal, or use case, or user story, etc.

```
Why?:
We do not have a card class for items
We need this to display item info in main menu
```

### What changes did you make or add to complete this commit?

```
I did these things:
Added pure implementation of ItemCard
together with its classes and passed
the tests locally
```

### What are the tags we can search or open `issue id` this commit relates to?

```
Tags?:
- ItemCard
- ItemCard.test
- Feature-#23
```

- If you still need examples, please view the commit history.

## Full example

```
models: Add item card

I made this commit because:
We do not have card for items
We need this to display item info in main menu

I did these things:
Added pure implementation of ItemCard
together with its classes and passed
the tests locally

Tags you can search for:
- ItemCard
- ItemCard.test
- Feature-#23
```
