# Keyword Management

Manage exactly what the bot monitors. You can set keywords globally or restrict them to specific channels.

---

## Commands

| Command | Description |
|---|---|
| `/add_keyword keyword: "your_keyword" channel: "IDs"` | Adds a keyword for specific channels. Channel restrictions apply to all keywords in the command. |
| `/remove_keyword "keyword"` | Removes a specific keyword from your list. |
| `/active_keywords` | Displays all currently monitored keywords. |

{% hint style="success" %}
**Pro tip — add multiple keywords at once!**
Separate keywords with a **comma** in a single command:

`/add_keyword keyword: "dunk,jordan,yeezy" channel: "IDs"`

All keywords in the command will share the same channel restrictions.
{% endhint %}
