# General Settings & Controls

Control the core monitoring functions and get a full overview of your configuration.

---

## On / Off

| Command | Description |
|---|---|
| `/activate_pinger` | Globally turns monitoring **on** for your user. |
| `/deactivate_pinger` | Globally turns monitoring **off** for your user. |

---

## Cooldown

| Command | Description |
|---|---|
| `/pinger_cooldown "minutes"` | Sets a cooldown **per channel and keyword**. |

{% hint style="info" %}
**How the cooldown works:**
If Channel A pings you for the keyword `"oasis"`, that channel goes on cooldown for that keyword. You will **still receive pings** for `"oasis"` from Channel B — the cooldown is channel-specific, not global.

**Recommended:** `/pinger_cooldown 5` to avoid spam.
{% endhint %}

---

## Settings Overview

| Command | Description |
|---|---|
| `/keywordpinger_settings` | Shows a complete overview of everything you have configured — Keywords, Cooldowns, Silently, Pushover, and more. |
