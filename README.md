PHP Coding Standards Fixer
==========================

The PHP Coding Standards Fixer tool fixes *most* issues in your code when you
want to follow the PHP coding standards as defined in the PSR-1 and PSR-2
documents.

If you are already using `PHP_CodeSniffer` to identify coding standards
problems in your code, you know that fixing them by hand is tedious,
especially on large projects. This tool does the job for you.

Installation & Usage
--------------------

To set up the CS-Fixer for Joomla, you'll need to do some manual set up. I'm working with @fabpot to integrate the fixes here to work in the original CS-Fixer, but that's not complete yet, so for now you'll need to do some set up. (I'm going to assume you're going to clone to the root of your user folder. Adjust paths below accordingly.)

- Clone this repo and checkout the `joomla` branch.
- If you're on a Mac or *nix box, alias the command via `alias php-cs-fixer-joomla="~/PHP-CS-Fixer/php-cs-fixer"`
- To use the fixer, migrate to the root of your project, checkout a clean branch, and run `php-cs-fixer-joomla fix .`
- Smile at how much time you just saved