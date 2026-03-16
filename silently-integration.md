# Silently Integration (Autostart)

Automatically start your Silently tasks the moment a keyword is matched — no manual action needed.

---

## 1. Setup

| Command | Description |
|---|---|
| `/silently key: "YourSilentlyKey"` | Sets your API key for the autostart feature. |
| `/silently_reset` | Removes your stored Silently key. |

{% hint style="warning" %}
**Requirement:** Silently must be **open in the menu** with your Quicktask folder configured for tasks to start automatically.
{% endhint %}

---

## 2. Control (On / Off)

| Command | Description |
|---|---|
| `/silently_activate` | Enables autostart — ideal when you're **away** and want the bot to handle everything. |
| `/silently_deactivate` | Disables autostart — use this when you're **present** and prefer to manage tasks manually. |

{% hint style="success" %}
**Tip:** Toggle autostart based on whether you're actively watching or stepping away. This gives you full flexibility.
{% endhint %}

---

## 3. Filters & Scheduling

| Command | Description |
|---|---|
| `/autostart_min_stock "amount"` | Only triggers tasks if stock is **above** this amount. Example: Set to `15` → any match with stock < 15 is ignored. Use the command again to overwrite. |
| `/autostart_schedule "start_time" "end_time"` | Activates tasks only within a set timeframe. Format: `XX.XX` (e.g., `14.00` to `23.00`). Timezone: **CEST**. |
| `/autostart_schedule_reset` | Removes the schedule — tasks run **24/7** as long as autostart is active. |
| `/autostart_disable_keyword` | Disables a specific keyword from triggering autostart. |
| `/autostart_enable_keyword` | Re-enables a previously disabled keyword. |
| `/autostart_disabled_keywords` | Shows all keywords currently excluded from autostart. |

{% hint style="info" %}
**Default behavior:** When autostart is active, it applies to **every** keyword by default. Use `/autostart_disable_keyword` to selectively exclude keywords — everything else continues to trigger tasks automatically.
{% endhint %}
