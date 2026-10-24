# Hack-O-Lounge

A small pixel-art social RPG for hackathons. Walk around the lounge, meet local demo characters, join the gathering table, and invite people to form a team.

## Run locally

Open `index.html` in a browser. The app uses plain HTML, CSS, canvas, and JavaScript. There is no server or build step.

## Local profiles and data

Profiles use a display name and email as a local lookup key. There is no email verification, password, or real account authentication. Profiles, chat messages, and team state stay in the current browser's local storage or memory. They do not sync between people or devices.

The group chat and team invitations are scripted demo interactions. No messages or profile details are sent to a backend.

## GitHub Pages

This is a static site and can be published from the repository root on the `main` branch using GitHub Pages. It does not provide shared login, chat, or team storage.
