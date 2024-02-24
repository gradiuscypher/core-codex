---
creation date: <% tp.file.creation_date() %>
tags: DailyNote <% tp.file.title.split('-')[0] %>
---


# <% tp.file.title %>

<< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>]]>>

## Tasks

#### Overdue

```tasks
not done
due before <% tp.date.now("YYYY-MM-DD") %>
```

#### Due Today

```tasks
not done
due on <% tp.date.now("YYYY-MM-DD") %>
```

#### New Today
- [ ]

## Meeting Log

### 0000:

## Daily Log



## Daily Check List

### Start of Day

- [ ] Check Email
- [ ] Check Slack
- [ ] Check Calendar – Time Block

### End of Day

- [ ] Show Offline
- [ ] Clean Unused Headings in Daily Log
- [ ] Check tomorrow's calendar

## Brain Dump



## Other Tasks

#### No Due Date

```tasks
not done
no due date
path does not include template
heading does not include Start of Day
heading does not include End of Day
```

#### Done Today

```tasks
done on <% tp.date.now("YYYY-MM-DD") %>
path does not include template
heading does not include Start of Day
heading does not include End of Day
```
