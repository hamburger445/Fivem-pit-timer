# 🚨 PT Timer Script for FiveM

A lightweight, client-side script for FiveM that adds a simple and configurable **PIT (Precision Immobilization Technique) cooldown timer** to assist in managing pursuit operations and cooldown periods.

---

## ✨ Features

- ✅ `/pt` command to start a countdown timer (default: 5 minutes)
- ✅ `/endpt` to stop the timer early
- ✅ Displays `"PIT is clear!"` when the timer ends
- ✅ Fully configurable via `config.lua`
- ✅ No dependencies – drag, drop, and go
- ✅ Clean on-screen text (position customizable)
- ✅ All command names are changeable

---

## 🛠 Configuration

Edit the `config.lua` file to suit your needs:

```lua
Config = {}

-- Timer duration in seconds
Config.TimerDuration = 300 -- 5 minutes

-- Screen position for the timer text (values between 0.0 and 1.0)
Config.TextPosition = {
    x = 0.88,
    y = 0.05
}

-- Custom command names
Config.Commands = {
    Start = "pt",
    Stop = "endpt"
}
