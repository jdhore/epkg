epkg(1) -- A friendly wrapper for Gentoo package managment commands.
====================================================================

## SYNOPSIS

`epkg` COMMAND [PACKAGE]

## DESCRIPTION

Run COMMAND optionally against PACKAGE(s).

## COMMANDS

  * `install`:
  Install a package (or packages).
  * `remove`:
  Remove a package (or packages).
  * `uninstall`:
  Alias for remove.
  * `search`:
  Search all enabled repositories for PACKAGE.
  * `update`:
  Update package listing and package search database.
  * `upgrade`:
  Check all packages on system for available upgrades.
  * `dist-upgrade`:
  Alias for upgrade.
  * `autoclean`:
  Remove unneeded distfiles.
  * `clean`:
  Remove ALL distfiles. Take care when using this command.
  * `forceremove`:
  Forcibly uninstall a package. Take care when using this command as reverse dependencies are NOT checked.
  * `listfiles`:
  List all files installed by a given PACKAGE.
  * `listinstalled`:
  List all packages currently installed matching a given pattern.
  * `provides`:
  List what package a provides a given filepath.
  * `verify`:
  Verify integrity of installed files for a given installed package.
  * `verifyall`:
  Verify integrity of all files on the system installed from the package manager.
  * `sysinfo`:
  Display some system information useful for debugging and support.

## EXAMPLES

`epkg install firefox-bin`:
  Install the firefox-bin package.

`epkg autoclean`

## SEE ALSO

emerge(1), eix(1), equery(1)
