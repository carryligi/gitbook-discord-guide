# Notifications (Pushover)

Get push notifications directly to your phone — even when you're not at your desk.

---

## Setup

| Command | Description |
|---|---|
| `/pushover "key"` | Sets your Pushover API key for mobile notifications. |
| `/pushover_priority` | Sets the alert sound/priority level (see levels below). |

---

## Priority Levels

{% hint style="info" %}
**Level 0 — Silent Alert**
Sends a notification with **no sound**. Useful for low-priority monitoring where you don't need to be interrupted.
{% endhint %}

{% hint style="warning" %}
**Level 1 — Alert with Sound**
Sends a notification with sound — **even if your phone is on mute**. Use this for important keywords you don't want to miss.
{% endhint %}

{% hint style="danger" %}
**Level 2 — High Priority**
Maximum urgency. Your phone will go **crazy** until the notification is acknowledged. Reserve for the most time-sensitive drops.
{% endhint %}
