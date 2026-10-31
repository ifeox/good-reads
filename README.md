# A collection of good reads

### Foundational
- [Programming as theory building](https://pages.cs.wisc.edu/~remzi/Naur.pdf)
> Peter Naur argues that the outcome of programming is not hte source code itself but the 
> the knowledge you gain in the act of programming

### Startups:
- [Is $10ARR the new early stage baseline](https://www.youtube.com/watch?v=pJVxm45FAco)

### Spec driven development:
- https://www.youtube.com/watch?v=EkH_uoybj8k
> A spec generated from code cant verify correctness
> Prose specification is a prompt with longer word count
> Code is law because it is a formal language you can reason about - Colin Eberhardt
> THe specification is the intent. It is what is true if you swap out the implementation of the system
> or change the programming language. This is the contract and the agent gets freedom on how to do the
> thing
> Crticism of spec driven developemtn is it is the new waterfall model. If you do write the entire
> spec upfront then, thats fair criticism. Furthermore, it is impossible to gather all the requirements
> upfront. Sometimes requirements are discovered during the implementation phase
> The specification should be executable

### Compound Engineering
- https://www.vincirufus.com/en/posts/compound-engineering/

### Harness Engineering
- https://codebastard.dev/from-context-engineering-to-harness-engineering-building-your-own-product-factory-to-your-taste

- https://codepick.dev/en/guides/meta-harness-2026/

- https://www.youtube.com/watch?v=9BVwdHAqvXg

### Code Review
- https://adamtornhill.substack.com/p/controlling-the-uncertainty-machine
> Code isn’t just produced and then lying dormant as an immutable artifact. Successful features attract change: improvements, extensions, and additional capabilities. Typically the most business-critical code experiences the largest volume of changes. Making those changes easy is what good software design is all about.

- https://medium.com/@delimiterbob/the-emperors-new-code-hype-vs-reality-of-ai-executable-specs-ff64d961e8ab
> There’s a reason we iterate, refactor, and revisit requirements. It’s because writing the code is how we figure out the spec as much as the other way around. Coding isn’t a mere clerical task. It’s a feedback loop for discovery. As you implement, you uncover missing details, test assumptions, and generate new ideas. In many cases, the spec lives in the code and evolves with it, rather than being an infallible oracle handed down from on high.

- https://ampcode.com/notes/thats-not-soc-2-compliant
> Pick one system and ask: “What risks are our pull requests actually managing here?” Then ask how else you could manage them. The answer doesn’t have to be pull requests.

- https://ghuntley.com/readable/
> Geoff Huntley, creator of Ralph Loops, argues that software does not need to be reable anymore and we need to invent new programming languages for agents

### Software Factories
- https://www.youtube.com/watch?v=Ib5GBkD555M
> Dex Horthy, founder of HumanLayer talks about agentic software factories and why you should still read the code

- https://www.youtube.com/watch?v=AsvzMlLyQ38

- https://www.youtube.com/watch?v=haUfb1ievTE

- https://www.youtube.com/watch?v=5KYCm0-OGL4
> Should you still learn to code? Absolutely. Yes. 

### AI safety
- https://www.cyera.com/blog/the-lethal-trifecta-why-ai-agents-require-architectural-boundaries
- https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/

### Model Context Protocol
- Neon Postgres - https://www.youtube.com/watch?v=BqRhBq-_kgE
> Initially mcp tools were a 1 to 1 mapping to an API
> API is fine grained and MCP is coarse grained
> Layered tool calls . Expose just 3. One tool to search all the available endpoints, tool to get details for a tool and one to call a specific tool
> Progressive Tool Discovery. Programmatic tool calling
> Raw endpoints, ergonomic endpoints


### Agent 2 Agent Communication
- Pi to Pi: https://www.youtube.com/watch?v=PIdETjcXNIk