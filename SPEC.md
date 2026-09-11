# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page Kitchen Helper site where a visitor selects a few pantry items and instantly sees matching recipe suggestions plus a grocery list of what they still need.
- **Audience:** Busy students and young adults/households who want to cook from what they already have before buying more groceries.
- **Requirements:** One working primary interaction (select pantry items → see recipes + grocery list); selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Clean, warm, modern consumer-app look — soft cream background, earthy greens, rounded cards, friendly food icons, simple high-contrast type, matching a mobile-app feel. ~20 sample pantry items and 8-10 sample recipes as static local data.
- **Test:** I can select pantry items, see recipe suggestions and a grocery list update live, confirm the grocery list never repeats an item I already marked as owned, and check one factual/boundary case (e.g., selecting zero items, or an item not used in any recipe). After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
