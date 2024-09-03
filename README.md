# Issues
This repos allows us to maintain our issues at a centralized place.

## Definition of Readiness
- [ ] Is the issue labeled with a `type` label (e.g. for story or task)?
- [ ] If it's a `task`, `bug` or something similar coming below stories ("level 3"): Is it labelled with an `area`?
- [ ] Is it assigned to at least one person?
- [ ] Is it assigned to a project board?
- [ ] If it's a `story` and there is an `epic` for it - does the `epic` refer to the `story`?
- [ ] If it's a `task` or `bug` and there is a story for it - does the `story` refer to the `task`/`bug`?

## Other Notes

- Prefix labels (i.e. `area: ...` or `type: ...`) are exclusive for their prefix: there can't be two `areas` or two `types` for a single ticket. If need for that arises, it's a hint that a ticket should be split further, e.g. a story into one ticket with `type: task`+`area: frontend` and another one with `type: task`+`area: backend`.
- Use the templates - we want to improve incrementally them based on our experiences with them.
- While the emoji and type in the issue title help to increase the readability - and therefore should be kept -, they don't replace the labels. So for example `🐛 Bug` in the title helps, but `type: bug` must still be assigned.
