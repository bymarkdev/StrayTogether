# 🐈 Stray Together

> A community-driven continuation of KangieDanie's original split-screen prototype for Stray.

## About

Hey! 👋

This is my **first public release**, so be nice :)

This project started because I wanted to play **Stray** with someone on the couch... only to discover that the original split-screen mod no longer worked on the latest Steam version.

Instead of giving up, I decided to figure out why.

That innocent little decision somehow turned into days of staring at logs, reverse engineering Unreal, questioning my life choices at 3am, and learning way more about UE4 than I ever expected.

The result is **Stray Together**.

It's built on top of **KangieDanie's** original prototype, but it's much more than a simple compatibility patch. A large part of the original implementation has been rebuilt to work with **UE4SS**, allowing the mod to run on the current Steam version while fixing a lot of the issues that made the original prototype unusable today.

This isn't a replacement for KangieDanie's work.

It's a continuation.

Their original prototype made local multiplayer possible in the first place, and this project simply tries to keep that idea alive while pushing it a little further.

Massive thanks to **KangieDanie** for creating the original foundation.

Seriously.

Without that first crazy experiment, none of this would've existed.

---

# ✨ Features

- ✅ Works on the latest Steam version of Stray
- ✅ Local split-screen multiplayer
- ✅ Compatibility fixes
- ✅ Stability improvements
- ✅ Better player spawning
- ✅ Improved level transitions
- ✅ Runtime split-screen management
- ✅ Cleaner logging
- ✅ Configurable player count (up to 4)

---

# 🎮 Controls

| Key | Action |
|------|--------|
| **F9** | Add a local player |
| **F8** | Remove the latest player |
| **F6** | Repair the player setup |
| **F7** | Debug player spawn |

---

# 📦 Installation

You'll need:

- A legitimate Steam copy of **Stray**
- **UE4SS**

Install UE4SS inside:

```text
Stray/Hk_project/Binaries/Win64
```

Then copy the **StraySplitScreen** folder into:

```text
Mods/
```

Finally, enable it inside:

```text
mods.txt

StraySplitScreen : 1
```

That's it.

You're ready to bully B-12 with a friend.

---

# ⚠️ Important

If you still have the old **UnrealEngineModLoader** version installed...

**Disable it.**

Seriously.

Running both versions at the same time usually ends with duplicate players, broken cameras, weird controllers or the game deciding that existing is optional.

Ask me how I know.

---

# ⚙️ Configuration

Everything can be configured inside:

```text
Mods/StraySplitScreen/Config/config.lua
```

You can change:

- maximum players
- keybinds
- controller behaviour
- repair options
- debug options
- logging
- and a few experimental settings

Want to try 3 or even 4 players?

Go for it.

Just remember...

Stray was designed for one cat.

I'm emotionally convincing it otherwise.

---

# ❤️ Credits

### Original split-screen prototype

**KangieDanie**

The person who proved this was even possible.

### Rework, compatibility fixes & continued development

**Mark**

Probably drinking too much coffee while reading Unreal logs.

### Special thanks

- UE4SS
- BlueTwelve Studio
- Everyone testing weird builds and sending logs instead of just saying "it doesn't work."

You people are heroes.

---

# 🚧 Current Status

The project is actively being improved.

If you find a bug, crash or some cursed behaviour...

Open an issue.

Attach your logs.

Tell me what happened.

"It broke."

...doesn't help much 😭

---

# ❤️ Final Note

This is my first public project.

I learned a ridiculous amount while making it, and honestly I never expected a random idea like "what if Stray had split-screen?" to end up here.

If you enjoy the mod, consider starring the repository.

And if you enjoy the idea behind it...

Please check out **KangieDanie's** original project too.

They started this whole thing.

I'm just trying to keep it alive.
