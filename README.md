AVCam
=====

Modernization and bug fixing of Apple's AVCam sample project

Features:

- memory leaks free
- uses Automatic Referent Count (ARC)
- modern Objective-C syntax
- minor UI fixes for iOS 7

Note
====
If you need to use the `AVCam` classes in a non-ARC project, you must selectively enable ARC on them.
It can be easily achieved by adding `fobj-arc` to Other Linker Flags in your project's build settings.
