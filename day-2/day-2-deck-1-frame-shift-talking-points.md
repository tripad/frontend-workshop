# Day 2 Deck 1: The Frame Shift — Talking Points

## Slide 1 — The Happy Path

- Ask the room: how many of you have designed an empty cart, an error toast, a no-internet screen, or an invalid input state?
- Most Figma student projects show the product when everything works.
- Name the pattern clearly: the happy path is useful, but it is not the whole product.
- Emphasize that slow networks, empty data, wrong inputs, denied permissions, server errors, and edge cases are design work too.
- Frame the day: today is about learning to see the parts of the product that usually stay invisible in static mockups.

## Slide 2 — What's a State?

- Define a state simply: what the interface shows in one specific situation.
- Use the cart example: same screen, different reality.
- Point to the four cart blocks and say: the frame is similar, but the user's situation has changed.
- Reinforce the phrase: you are not designing a screen, you are designing every state that screen can be in.
- Make this feel practical, not theoretical. These states become components, conditions, and flows in real products.

## Slide 3 — Designing for Time

- Figma trains students to think in space: layout, alignment, hierarchy, spacing.
- Real products also require thinking in time: what happens after a tap and before the result.
- The gap between tap and result is where products feel solid or broken.
- Loading skeletons, optimistic UI, disabled buttons, retry actions, and error toasts are all answers to the same question: what fills the gap?
- Pause on the "???" in the timeline. That middle zone is the design challenge.

## Slide 4 — Live Audit Companion

- Keep this slide sparse because the phone mirror is the main content.
- Mirror a real app such as Zomato, Uber, or Swiggy.
- Ask students to call out states as they see them.
- Write discovered states on the board as a live inventory.

Demo cues:

- Open the app cold and point out the first loading or empty state.
- Trigger a search with zero results.
- Show the empty cart.
- Toggle airplane mode mid-flow.
- Try an invalid pincode, address, or input.

## Slide 5 — Core State Vocabulary

- Present this as the shared vocabulary for the rest of Day 2.
- Empty and error states are often where designers mature because they require judgment, copy, hierarchy, and recovery.
- Loading is not decoration. It sets expectations and prevents the user from feeling stuck.
- Partial is the one designers forget most often. Real apps often show some data while more is still arriving.
- Success needs a next step, not just a checkmark.
- Edge cases are not rare in aggregate. Weird inputs happen constantly across large user bases.

## Slide 6 — The Other States Worth Naming

- These states are usually invisible in Figma because they are triggered by things outside the screen: network, OS, server, cache, permissions.
- Offline and permission denied are especially common in real use, especially on unreliable mobile networks.
- Permission denied should not feel like the app is punishing the user for saying no.
- Stale data matters because old information can mislead users.
- Rate-limited or blocked states are less common in student projects, but very real in apps that talk to APIs.
- Connect this to AI tools: if you do not name these states in the prompt, the tool will usually design only the happy path.

## Slide 7 — Before We Open Stitch

- Recap the three ideas slowly:
  1. A screen has many states.
  2. States are about time as much as space.
  3. The vocabulary gives us a shared language.
- Bridge into the next block: first prompt Stitch normally, then prompt it with state thinking.
- Set up the comparison: students should see how the prompt changes the quality of the output.
- The goal is not just to make prettier screens. The goal is to ask for more complete product thinking.
