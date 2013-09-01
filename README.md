git-hooks
=========

Fork of Bartek's hook adapted for Ubuntu and Drupal.
These hooks are prepared to work in bash. I didn't test hooks from any IDE or Windows Git like Tortoise Git.


For now there is only one pre-commit hook which check the code for 'development-only' instruction such as:
* var_dump,
* print_r

or Drupal Devel's debug functions e.g. dpm().

Git will abort commit if it find these instrucion and show where they are (file name and line of code).

