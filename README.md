# idea-to-hell-yes

A Claude Code plugin that turns an idea into a testable "hell yes" hypothesis: **who would be weird *not* to buy it?**

Give it a product idea, a sales call transcript, a pile of notes, or an existing company, and it will either:

1. Produce at least one testable hypothesis of a buyer who *can't not buy*, or
2. Tear down your own buyer hypothesis (if it's wrong) and propose at least one alternative.

A "can't not buy" buyer is someone who (a) is trying to do something right now that they can't not do, and (b) can't do it with their existing tools, methods, or options.

## Install

In Claude Code:

```
/plugin marketplace add rssnyder13/idea-to-hell-yes
/plugin install idea-to-hell-yes@idea-to-hell-yes
```

## Usage

Run the command directly:

```
/hell-yes an API for APIs
/hell-yes AI notetaker for financial advisors — my hypothesis: any advisor who hates taking notes
```

Or just ask naturally ("who would actually buy this?", "pressure-test my ICP") and Claude will pick up the `idea-to-hell-yes` skill automatically.

## Layout

```
.claude-plugin/
  plugin.json         # plugin manifest
  marketplace.json    # lets this repo be added as a marketplace
skills/idea-to-hell-yes/SKILL.md   # the method
commands/hell-yes.md               # /hell-yes slash command
```
