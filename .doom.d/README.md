# My Doom Emacs config

## Versioning

Check if env file generated at install is worth versioning:

```
Generate an envvar file? (see `doom help env` for details) (y or n) y
> Generating envvars file
  ✓ Generated ~/.emacs.d/.local/env
```

## Post install

Message displayed at the end of the install process:

✓  Finished! Doom is ready to go!

But before you doom yourself, here are some things you should know:

1. Don't forget to run 'doom sync', then restart Emacs, after modifying
   ~/.doom.d/init.el or ~/.doom.d/packages.el.

   This command ensures needed packages are installed, orphaned packages are
   removed, and your autoloads/cache files are up to date. When in doubt, run
   'doom sync'!

2. If something goes wrong, run `doom doctor`. It diagnoses common issues with
   your environment and setup, and may offer clues about what is wrong.

3. Use 'doom upgrade' to update Doom. Doing it any other way will require
   additional steps. Run 'doom help upgrade' to understand those extra steps.

4. Access Doom's documentation from within Emacs via 'SPC h d h' or 'C-h d h'
   (or 'M-x doom/help')

Have fun!