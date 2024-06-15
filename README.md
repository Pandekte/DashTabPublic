# DashTabPublic
DashTab is a comprehensive browser extension designed to help users efficiently manage their bookmarks. This extension provides various functionalities, including bookmark management, to-do list management, custom background settings, and dark mode toggling.

# Bookmark Manager Extension

## Introduction

Bookmark Manager is a comprehensive browser extension designed to help users efficiently manage their bookmarks. This extension provides various functionalities, including bookmark management, to-do list management, custom background settings, and dark mode toggling.

## Features

- **Bookmark Management**: Add, edit, delete, import, export, and organize bookmarks.
- **To-Do List Management**: Add, complete, and delete to-do items with a simple interface.
- **Custom Backgrounds**: Customize the background of your bookmark manager interface.
- **Dark Mode**: Toggle dark mode for a better visual experience in low-light conditions.

## Installation

To install this extension:

1. Go to the chromestore and install extension: https://chromewebstore.google.com/detail/dashtab/ojpihaakeniapmjfbgnieieecpejlhid

## Usage

### Event Listener

```javascript
document.addEventListener("DOMContentLoaded", function () {
  renderBookmarks();
  setupEventListeners();
  initializeSettings();
  initializeToDoList();
  loadBookmarkOpeningSetting();
});
