# Silently Integration (Autostart)

Advanced features to automatically start your tasks via Silently when a keyword is matched.

## 1. Setup

| Command | Description |
|---------|-------------|
| `/silently key: "YourSilentlyKey"` | Sets your API key for the autostart feature. |
| `/silently_reset` | Removes your stored Silently key. |

> **Requirement:** Silently must be open in the menu (and your Quicktask folder setup) for tasks to start automatically.

## 2. Control (On/Off)

| Command | Description |
|---------|-------------|
| `/silently_activate` | Enables the autostart feature (useful to turn on when you are away). |
| `/silently_deactivate` | Disables autostart (useful if you are present to manage tasks manually). |

## 3. Filters & Scheduling

| Command | Description |
|---------|-------------|
| `/autostart_min_stock "amount"` | Only starts tasks if stock is above this amount. Example: If set to `15`, any match with stock < 15 won't trigger tasks. |
| `/autostart_schedule "start_time" "end_time"` | Activates tasks only within a timeframe. Format: `XX.XX` (e.g., `14.00` to `23.00`). Timezone: **CEST**. |
| `/autostart_schedule_reset` | Resets the schedule — tasks run 24/7 as long as `/silently_activate` is on. |
| `/autostart_disable_keyword` | Disables a selected keyword for the autostart feature. |
| `/autostart_enable_keyword` | Re-enables a previously disabled keyword. |
| `/autostart_disabled_keywords` | Shows all currently disabled keywords. |

> **Default behavior:** When autostart is activated, it is active for **every** keyword — unless you have specifically added a keyword to the disabled list. This lets you stay in full control of which keywords trigger tasks automatically.
