# Neatly

Everything in its place.

Neatly is a local Windows folder organizer. Preview individual moves, choose what moves, save reusable filename rules, and undo completed moves from history.

## Download

**[Download Neatly 0.1.2 for Windows x64](https://github.com/robertbradley-oss/neatly-releases/releases/download/v0.1.2/Neatly-Setup-0.1.2-x64.exe)**

[Release notes and checksum](https://github.com/robertbradley-oss/neatly-releases/releases/latest)

## Install

1. Download the installer and close Neatly if it is running.
2. Run setup, then open **Neatly** from the Start menu.
3. Choose **Try a sample folder** to explore preview, move, and undo with fictional files.

Requires Windows 10 version 1809 or later, or Windows 11, on x64. Python is included. Setup installs Microsoft Edge WebView2 if missing; that step requires internet access. Folder organization runs locally.

The installer is unsigned. Windows may show an unknown-publisher or SmartScreen warning.

Run a newer installer to upgrade. Uninstall through Windows Installed apps. History, saved rules, and personal files are preserved. Automatic updates are not included.

## Before organizing

Neatly considers immediate files; subfolders remain in place. Review the proposed moves and keep the folder idle while applying or undoing. Changed files and occupied paths are reported as conflicts. Keep your history for undo, and maintain backups: Neatly is not a backup system. Avoid source repositories and application-managed folders.

History and saved rules are stored in `%LOCALAPPDATA%\Neatly\history`.

## About this repository

This repository distributes Neatly's Windows installers and release notes. The application source is maintained privately.
