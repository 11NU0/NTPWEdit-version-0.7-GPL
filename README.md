# NTPWEdit-version-0.7-GPL

NTPWEdit is a password editor for Windows NT based systems (like Windows 2000, XP, Vista, 7, 8, 10), it can change or remove passwords for local system accounts. This program can NOT decrypt passwords or change domain, Active Directory or Microsoft account passwords.

Project website: http://www.cdslow.org.ru/en/ntpwedit/

## Overview

NTPWEdit changes passwords by direct modifying file C:\WINDOWS\SYSTEM32\CONFIG\SAM. When running, operating system blocks any access to this file, so password editor must be executed on another Windows copy.

## Usage Methods

Some methods for use this program:

- Boot Windows PE environment from CD-ROM or flash-drive and launch NTPWEdit
- Boot command line rescue mode from Windows Vista or newer distribution media
- Attach hard drive to another computer, and edit passwords there
- Boot system from separate partition (if multiple OS are installed)

## About

NTPWEdit is based on sources from The Offline NT Password Editor (chntpw) (c) 1997-2014 Petter Nordahl-Hagen. In fact, NTPWEdit is a Win32 GUI port of chntpw.
