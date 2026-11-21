# Check Agent Skill Visibility in Google

Diagnose why individual agent skill pages are missing from Google even when their homepage or catalog appears. Compare branded skill names with task queries, check index evidence when Search Console is available, and record the next fix for each affected page.

## Install

```sh
npx skills add arm-pz/check-skill-visibility
```

## Try it

> Google shows our homepage, but I can't find our skill landing pages. Check the five skills that matter most and tell me which issues we can fix.

Provide the catalog URL, the priority skill pages, and any Search Console evidence you can share. The skill returns search observations and a JSON handoff with evidence, actions, and verification steps. Public search results alone can establish what appeared for the checked query. Use URL Inspection for Google's index status and selected canonical.

Send the [findings handoff](references/handoff.md) to [Fix Skill Visibility](https://github.com/arm-pz/fix-skill-visibility) to apply the supported changes. Part of [Skillsmith by Caffeinity](https://skillsmith.tech/).
