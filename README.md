Password Delay Shell Utility
=========================

[![Platforms macOS](https://img.shields.io/badge/Platforms-macOS-lightgray.svg?style=flat)](http://www.apple.com/macos)
[![License Apache](https://img.shields.io/badge/License-APACHE2-blue.svg?style=flat)](https://www.apache.org/licenses/LICENSE-2.0.html)

A shell utility that sets the screen saver grace period before the system prompts the user to re-authenticate. Previously, this could be set with the `askForPasswordDelay` key in the `com.apple.screensaver` preference domain. However, this has no effect in macOS 10.13.4 (High Sierra) and above.

Usage is `pwdelay delay` where delay is the number of seconds to wait after sleep or screen saver begins before requiring a password.
