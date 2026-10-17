# FocusDay

A simple daily task list with a Pomodoro timer. Plain HTML/CSS/JS, no build step, no backend, no accounts.

Your tasks, history and settings are saved on your own device. Nothing is sent to a server.

## Host it (GitHub Pages)

1. Create a GitHub repo, for example `focusday`.
2. Upload everything in this folder to the repo root, so `index.html` is at the top level.
3. Settings → Pages → "Deploy from a branch" → `main` → `/ (root)` → Save.
4. After a minute the app is live at `https://YOUR_GITHUB_USERNAME.github.io/focusday/`.

On a phone, open the link in Chrome and choose "Add to Home screen" or "Install app".

## Features

- Up to 10 tasks per day.
- Unfinished tasks don't carry over. You can move one to tomorrow, but then that day won't earn a sticker.
- A 🌟 sticker when every task for the day is done.
- Pomodoro timer: 15/5, 25/5, 50/10, with a chime.
- Light, dark and pastel themes, 7-day history, guided tour.
- Works offline after the first load.

## Limitations

- Clearing site data or uninstalling can delete your tasks. There is no backup or sync.
- Test on real Android and iOS devices.

## Test checklist

- [ ] The tour opens on a fresh profile, can be skipped, and doesn't reopen. Guide replays it.
- [ ] 15/5, 25/5 and 50/10 can all be selected.
- [ ] Add 10 tasks. The 11th is blocked.
- [ ] Complete all tasks and check the 🌟 shows. Leave one undone and it doesn't.
- [ ] Move a task to tomorrow. It leaves today, today can't earn a sticker, and it shows up on the next date.
- [ ] An unfinished task you didn't move does not carry over.
- [ ] Refresh and reopen the installed app. Tasks and settings are still there.
- [ ] Open the app offline after one successful load.
