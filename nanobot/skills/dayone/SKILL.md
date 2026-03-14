---
description: Create and manage journal entries in Day One using the
  `dayone` CLI. Supports text, tags, journals, dates, time zones,
  attachments, coordinates, and starred entries.
name: dayone
---

# Day One Skill

Use the `dayone` CLI to create journal entries in Day One.

The Day One macOS app must be installed.\
The CLI requires the Day One app to exist at:

-   /Applications/Day One.app
-   Or define DAYONE_APP_PATH environment variable.

------------------------------------------------------------------------

## Create Entry

Create a simple entry:

``` bash
dayone new "Today I completed MCP integration."
```

If no text is provided, standard input will be used:

``` bash
echo "Build completed successfully." | dayone new
```

Disable stdin behavior:

``` bash
dayone new --no-stdin
```

------------------------------------------------------------------------

## Create Entry with Tags

Assign one or more tags:

``` bash
dayone new "Deployment successful." --tags Work Backend
```

Tags with spaces must be escaped:

``` bash
dayone new "Won the match!" --tags Soccer\ Match Win
```

------------------------------------------------------------------------

## Create Entry in Specific Journal

Journal must already exist:

``` bash
dayone new "Sprint planning completed." --journal Work
```

------------------------------------------------------------------------

## Create Entry with Date

Specify custom date:

``` bash
dayone new "Backdated entry." --date="2026-02-16 10:30:00"
```

Natural formats supported:

``` bash
dayone new "Reflection entry." --date="Last Tuesday"
```

------------------------------------------------------------------------

## ISO 8601 Date (UTC)

``` bash
dayone new "ISO test entry." --isoDate=2026-02-16T03:00:00Z
```

------------------------------------------------------------------------

## Specify Time Zone

Using IANA time zone name:

``` bash
dayone new "Anchorage entry." -z America/Anchorage
```

Using GMT offset:

``` bash
dayone new "GMT entry." --time-zone GMT-0700
```

------------------------------------------------------------------------

## All-Day Entry

Marks entry as spanning entire day:

``` bash
dayone new "Company anniversary." --date="2026-02-20" --all-day
```

------------------------------------------------------------------------

## Star Entry

``` bash
dayone new "Major milestone achieved." --starred
```

------------------------------------------------------------------------

## Add Attachments

Supported: image/photo, video, audio, PDF.\
Maximum 10 attachments.

When using -a, you must use -- before new.

Single attachment:

``` bash
dayone -a ~/Pictures/photo.jpg -- new "Morning coffee."
```

Multiple attachments:

``` bash
dayone -a ~/Pictures/1.jpg ~/Documents/file.pdf -- new "Daily log with files."
```

Position attachment in text:

``` bash
dayone -a ~/Pictures/photo.jpg -- new "Here is the image: [{attachment}]"
```

------------------------------------------------------------------------

## Add Location Coordinate

Latitude followed by longitude:

``` bash
dayone new "Visited new cafe." --coordinate -6.2000 106.8167
```

------------------------------------------------------------------------

## Version and Help

Display help:

``` bash
dayone --help
```

Display version:

``` bash
dayone --version
```

Enable verbose logging:

``` bash
dayone new "Debug entry." --verbose
```

------------------------------------------------------------------------

# Example Advanced Entry

``` bash
dayone new "MCP integration test passed. JWT validation working." \
  --journal Work \
  --tags MCP Backend DevLog \
  --date="2026-02-16 09:45:00" \
  --starred
```
