---
layout: page
title: Contributing
permalink: /contributing/
---

First of all, thanks for taking the time to contribute to my project. It really means a lot. Down below are some guidlines you should follow when submitting merge requests.

This page is simply so I don't have to update `CONTRIBUTING.md` on every project when I want to make changes.

**Note:** Each project likely has its own smaller subset of rules whilst also linking here. Please ensure you read those as well.

### General

#### Notes

 * Comment your code. I want to support it in the future, I need comments
 * Have informative git commit messages
 * Follow the [styling](#styling) notes below

#### Pull Requests
 * Fork the project
 * Clone down your fork (`git clone git://github.com/username/project`)
 * Create a feature branch (`git checkout -b my-new-feature`)
 * Develop your feature/bug fix
 * If necessary, rebase your commits into logical chunks, without errors. I don't want to be adding extra commits for things like *Updating README* - do all this in the one commit
 * Push the branch up (`git push my-new-feature`)
 * Send a pull request for your branch ensuring you've followed these guidlines

### Styling

Unless the code and/or project has specific requirements that contradict below, follow these coding guidlines:

 * No trailing whitespaces, blank lines should have no spaces
 * Include meaningful whitespace between lines of code - make sure its readable
 * Ensure there is a newline/`eol` character at the end of every file  
   You can achieve this in many editors by doing the below (shamelessly stolen from <https://robots.thoughtbot.com/no-newline-at-end-of-file>):

> * For Vim users, you’re all set out of the box! Just don’t change your eol setting.
 * For Emacs users, add `(setq require-final-newline t)` to your `.emacs` or `.emacs.d/init.el` file.
 * For TextMate users, you can install the [Avian Missing Bundle](https://github.com/elia/avian-missing.tmbundle#strip-trailing-whitespace-on-save) and add TM_STRIP_WHITESPACE_ON_SAVE = true to your `.tm_properties` file.
 * For Sublime users, set the `"ensure_newline_at_eof_on_save"` option to `true`.
> * For RubyMine, set “Ensure line feed at file end on Save” under “Editor.”

### Questions?

If you're confused on any of the above, shoot me an email or [file a issue on GitHub](https://github.com/Mooash/mooash.github.io).
