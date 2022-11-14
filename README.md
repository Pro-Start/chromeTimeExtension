# Chrome Extension for Time Tracking

A basic time module for the getting the current time and date. This module is a part of the another project called the 'theTimeR'.

### Installation

1. Clone this repository

2. Go to `chrome://extensions/`

3. Go to `Developer mode`

4. Go to `Load unpacked extension...`

5. Go to the folder where you cloned this repository

### Breifing

#### Basic declaration

```json
"name": "Time",
"version": "1.0",
"description": "A basic time module for the getting the current time and date. This module is a part of the another project called the 'theTimeR'.",
"manifest_version": 3,
"author": "pratik kabade",
```

#### Icon declaration

```json
"icons": {
    "128": "images/logo.png"
},
```

#### Actions

```json
"action": {
    "default_popup": "index.html",
    "default_title": "Click Me"
},
```

#### Shortcuts

```json
"commands": {
    "favorite-command": {
        "suggested_key": {
        "default": "Alt + T"
        },
        "description": "Open Page",

        "global": true
    }
}
```
