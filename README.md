# Low to High Dimensionality

An illustrated essay on why complex things should be built simple first, and how to decide when to add complexity.

**Live page:** https://seanman005.github.io/DIMENSIONALITY/

## The main idea

The more connected parts a system has, the harder it is to fix when something goes wrong.

- **Simple system:** when something fails, you can tell exactly what broke. Fixing it is cheap.
- **Complex system:** when something fails, you only know *something* broke. Fixing it means undoing a lot of work.

So the best way to build anything is to start simple, prove each layer works, and only then add more complexity on top.

## What the essay covers

1. **The cost of mistakes.** Errors are cheap to fix early and expensive later, so build in order from simple to complex.
2. **Why order matters.** Each tested layer makes the next layer's problems easier to spot. Your ability to judge what works is built up step by step.
3. **When to keep going or stop.** At every step, ask one question: is more work here still paying off? If yes, go deeper. If no, lock it in and move on.
4. **Balancing breadth and depth.** Exploring too many options spreads you thin. Committing too early locks in the wrong choice. The best balance leans toward depth, while keeping some room to explore.
5. **The limits of the person building.** People can only track about 2–3 connected things at once. The way past that limit is to settle and simplify parts of the problem ahead of time, so there's less to hold at once.

## Examples used

Sculpting rough shapes before details, solving a puzzle's edges before its middle, and getting the core idea of a piece of writing right before polishing the words.

## Related ideas in AI and engineering

- Training on easy examples before hard ones (curriculum learning)
- Starting with simple models before complex ones to avoid overfitting
- Balancing exploring new options against using what already works (explore vs. exploit)

## Built with

HTML, hand-drawn SVG diagrams. 

## Author

Sean Obiacoro — Mechanical Engineering (Systems Emphasis), University of Utah, May 2027
