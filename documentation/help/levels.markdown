---
layout: page
title: "Help: levels"
---

{% comment %}

Please submit changes to
- https://github.com/irssi/irssi/blob/master/docs/help/in/levels.in


{% endcomment %}
<nav markdown="1">
[Help index](/documentation/help)
</nav>

### Description ###

These are the message levels that are used throughout Irssi; they describe
what kind of message is displayed.

These are the common levels you can use:


| `ACTIONS` | Actions by a nickname. |
| `CLIENTCRAP` | Irssi's internal messages. |
| `CLIENTERROR` | Irssi's internal error messages. |
| `CLIENTNOTICE` | Irssi's internal notices. |
| `CRAP` | Can be almost anything. |
| `CTCPS` | CTCP messages. |
| `DCC` | DCC protocol related messages. |
| `DCCMSGS` | DCC chat messages. |
| `INVITES` | An invite is received. |
| `JOINS` | A nickname joins a channel. |
| `KICKS` | A nickname gets kicked from a channel. |
| `MODES` | A channel mode is modified. |
| `MSGS` | Private messages. |
| `NICKS` | A nickname changes to another nickname. |
| `NOTICES` | Notices sent from a nickname. |
| `PARTS` | A nickname leaves a channel. |
| `PUBLIC` | Public messages in a channel. |
| `QUITS` | A nickname disconnects from IRC. |
| `SNOTES` | Notices sent from a server. |
| `TOPICS` | A channel topic is modified. |
| `WALLOPS` | A wallop is received. |
{:.table.kv}

These are the special levels you can use:


| `HILIGHT` | The text is highlighted. |
| `NEVER` | Never ignores or logs the message. |
| `NO_ACT` | Doesn't trigger any activity in the statusbar. |
| `NOHILIGHT` | The text is not highlighted. |
{:.table.kv}

When using levels from Irssi scripts, you need to prepend the level with
    'MSGLEVEL_'; for example 'CRAP' becomes 'MSGLEVEL_CRAP'.

