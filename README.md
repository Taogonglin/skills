# Prompt Optimizer Skill

A Claude Code skill for writing efficient prompts that maximize hit rate, minimize revision rounds, and increase template reusability.

## Installation

```bash
# Install as Claude Code plugin
claude plugin add Taogonglin/skills
```

Or manually:

```bash
# Clone and link
git clone https://github.com/Taogonglin/skills.git
cd skills
claude plugin link .
```

## Features

- **Efficiency Formula**: Measure prompt quality by Hit Rate × Reusability ÷ Revision Rounds
- **Pipeline Structure**: Split complex prompts into 3 stages instead of mega prompts
- **XML Tag Boundaries**: Isolate rules, context, examples, and output format
- **Bidirectional Examples**: Show both good and bad examples with explanations
- **Precise Action Language**: Verb + Object + Constraint pattern
- **Temperature Guide**: Match temperature to task tolerance

## Quick Reference

**Good Prompt =**
1. Single, clear goal
2. XML-structured sections
3. Precise verbs with objects
4. Bidirectional examples
5. Context before question
6. Positive instructions first
7. Explicit output format

## Source

Based on [this Twitter thread](https://x.com/RookieRicardoR/status/2028107199839690908) by @RookieRicardoR.

## License

MIT