Welcome to DREAMM 2.1.2!
DREAMM 2.1.2 is a minor maintenance release of DREAMM 2.1 focused on frontend integration

For extensive documentation, check out https://aarongiles.com/dreamm/docs/v21

For latest updates, check out https://aarongiles.com/dreamm

If you encounter any issues, please email dreamm@aarongiles.com

Changes since 2.1.1
===================
* Added command line option -option <key>=<value> to control parameters from an external frontend
* Added -fullscreen and -window options as shortcuts for -option window/fullscreen=true/false
* Fixed launching Behind the Magic/Episode 1 Insider's Guide from the command line
* Fixed restart when launching from command line
* Fixed problem with verifying installed games when subfolders also contained games (e.g., DOTT)
* Disallowed direct launching of installers/upgraders from the command line (use -install instead)
* Added support for older ZIP compression types
* Added support for Indiana Jones and the Last Crusade (FM Towns) version 1.5.13
* Added support for Indiana Jones and the Fate of Atlantis (Japanese)
* Added support for new verified Secret of Monkey Island (Spanish) version
* Added support for Jedi Knight (French) with incorrect CD 2 (which is how it seems to have shipped)
* Removed Zak McKracken (Spanish) as it is a fan translation

Changes since 2.1
=================
* Fixed error/lack of sound with some versions of Yoda Stories
* Fixed unpredictable audio synchronization in Mortimer
* Fixed joystick in Outlaws (and other Winodws games)
* Fixed ARM-specific hangs in Infernal Machine menus
* Improve handling of very long pathnames during installation
* Improve behavior of Windows emulation process cleanup to reduce crashes
* Fix crashes when exiting Indiana Jones and His Desktop Adventures
* Fix race condition when starting up the 3D rendering threads
* Fix occasional crash when rendering overlays with custom images
* Support version 3 MDS image files
* Add support for a number of new international releases
