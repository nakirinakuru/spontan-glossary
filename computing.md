Computing Glossary
=====================

## Operating System

* Executable and Linkable Format (ELF)

  A common standard file format for executable files, object code, shared libraries, and core dumps. By design, ELF is flexible, extensible, and cross platform, not bound to any given central processing unit (CPU) or instruction set architecture.

  Filename extension: `none`, `.axf`, `.bin`, `.elf`, `.o`, `.prx`, `.puff`, `.ko`, `.mod` and `.so`

  The ELF format has replaced older executable formats in various environments. 
  - It has replaced a.out and COFF formats in Unix-like operating systems: Linux, Solaris, IRIX, FreeBSD, NetBSD, HP-UX, MINIX, etc
  - Non-Unix adoption: OpenVMS, BeOS, Haiku, Windows 10 Anniversary Update using the Windows Subsystem for Linux, etc.
  - Game console: PlayStation portable, Nintendo DS, Wii, etc
  - Android uses ELF .so libraries for the Java native Interface. With Android Runtime (ART), the default since Android 5.0 "Lollipop", all applications are compiled into native ELF binaries on installation.