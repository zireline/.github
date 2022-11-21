## Commit Guidelines

> NOTE: subject to change

- We use 50/72 standard for commits. 50 characters max
  for the title (excluding module prefix), an empty line, and then a
  full description of the commit, wrapped to 72 columns max. See this
  link for more information: http://chris.beams.io/posts/git-commit/

- Make sure commit titles are always in present tense, and are not
  followed by punctuation.

- Prefix each commit's titles with the module name, followed by a colon
  and a space (unless modifying a file in the base directory). After
  that, the first word should be capitalized.

  So for example, if you are modifying the API_service module:

  ```
    API_service: Fixed bug with wrong data
  ```

  Or for web_ui:

  ```
    web_ui: Fixed card not displaying
  ```

- If you still need examples, please view the commit history.
