# Laravel Menus (Fork)

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)

This is a **maintained fork** of `nwidart/laravel-menus` with extended support for **Laravel 9, 10, 11, and 12**.  
The original package is no longer actively maintained, but this fork ensures compatibility with modern Laravel versions.

---

## Version Compatibility

| **Laravel** | **laravel-menus** |
|-------------|--------------------|
| 5.4         | ^0.5               |
| 5.5         | ^1.0               |
| 5.6         | ^2.0               |
| 5.7         | ^3.0               |
| 5.8         | ^4.0               |
| 6.x         | ^5.0               |
| 8.x         | ^7.0               |
| 9.x         | dev-main (this fork) |
| 10.x        | dev-main (this fork) |
| 11.x        | dev-main (this fork) |
| 12.x        | dev-main (this fork) |

---

## Installation

In your Laravel project `composer.json`, add:

```json
"repositories": [
    {
        "type": "vcs",
        "url": "git@github.com:kinfarn/laravel-menus.git"
    }
],
"require": {
    "nwidart/laravel-menus": "dev-main"
}
