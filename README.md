# ICP

A Claude Code plugin that turns an idea into a testable ICP hypothesis: **who would be weird *not* to buy it?**

Give it a product idea, a sales call transcript, a pile of notes, or an existing company, and it will either:

1. Produce at least one testable hypothesis of a buyer who *can't not buy*, or
2. Tear down your own buyer hypothesis (if it's wrong) and propose at least one alternative.

A "can't not buy" buyer is someone who (a) is trying to do something right now that they can't not do, and (b) can't do it with their existing tools, methods, or options.

## Install

In Claude Code:

```
/plugin marketplace add rssnyder13/icp
/plugin install icp@icp
```

## Usage

Run the command directly:

```
/icp an API for APIs
/icp AI notetaker for financial advisors — my hypothesis: any advisor who hates taking notes
```

Or just ask naturally ("who would actually buy this?", "pressure-test my ICP") and Claude will pick up the `icp` skill automatically.

## Layout

```
.claude-plugin/
  plugin.json         # plugin manifest
  marketplace.json    # lets this repo be added as a marketplace
skills/icp/SKILL.md   # the method
commands/icp.md       # /icp slash command
```
