# Chrome-Extension (Leads-Tracker)

A simple Chrome extension built with HTML, CSS, and JavaScript that allows users to save and manage website links (leads) directly from their browser.
This project is part of the Scrimba JavaScript Course and demonstrates working with the DOM, localStorage, and Chrome APIs.

## Features

Save Input: Add custom links manually using the input field.

Save Current Tab: Instantly save the URL of your active browser tab with one click.

Delete All: Double-click the delete button to clear all saved leads.

Persistent Storage: All saved links are stored in your browser’s localStorage, so they stay even after refreshing or closing the page.

Dynamic Rendering: Links are displayed dynamically as clickable list items using template strings and DOM manipulation.

## Technologies Used

HTML5 – structure of the web page
CSS3 – styling and layout
JavaScript (ES6) – functionality and logic
Chrome Tabs API – to capture the current tab’s URL
localStorage – to store leads persistently

## How It Works

Type a URL in the input field and click "SAVE INPUT" to store it.

Click "SAVE TAB" to automatically save your current tab’s URL.

Your saved links appear below as clickable hyperlinks.

Double-click "DELETE ALL" to clear the list and reset storage.

