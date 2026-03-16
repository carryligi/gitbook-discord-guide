# Best Usage Workflow

Follow these steps in order for the optimal setup from scratch.

---

{% hint style="success" %}
**Step 1 — Add your keywords**
Start with `/add_keyword`. Use commas to add multiple keywords at once:
`/add_keyword keyword: "dunk,jordan,yeezy" channel: "IDs"`
{% endhint %}

{% hint style="success" %}
**Step 2 — Link Silently**
Connect your Silently account with `/silently key: "YourKey"`, then run `/silently_activate` to enable autostart.
{% endhint %}

{% hint style="success" %}
**Step 3 — Refine your filters**
Avoid false starts by setting `/autostart_min_stock` and an `/autostart_schedule` if you only want tasks to run during certain hours.
{% endhint %}

{% hint style="success" %}
**Step 4 — Set a cooldown**
Run `/pinger_cooldown 5` to prevent getting spammed for the same keyword across rapid restocks.
{% endhint %}

{% hint style="success" %}
**Step 5 — Activate & wait**
Enable monitoring with `/activate_pinger`. That's it — wait for DMs and let the bot do the work!
{% endhint %}

{% hint style="info" %}
**Smart usage:** Combine `/autostart_schedule` with `/autostart_min_stock` to only trigger tasks during peak hours and for meaningful stock levels. Less noise, more signal.
{% endhint %}
