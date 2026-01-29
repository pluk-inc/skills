# emilkowal-animations-swift

A comprehensive SwiftUI and AppKit animation skill following the [Agent Skills](https://agentskills.io) open format. Extends AI coding agents with animation best practices adapted from Emil Kowalski's web animation principles and Framer Motion guidelines for Apple platforms.

## Overview

**80 rules** across **10 categories** for iOS 17+ SwiftUI and macOS AppKit animations:

| Category | Rules | Impact |
|----------|-------|--------|
| Timing Curves & Easing | 10 | CRITICAL |
| Duration & Timing | 5 | CRITICAL |
| Animation Properties | 7 | HIGH |
| Transforms & Effects | 7 | HIGH |
| Gesture & Interaction | 14 | HIGH |
| Transitions & Navigation | 10 | MEDIUM-HIGH |
| Scroll & Parallax | 6 | MEDIUM |
| Strategic Animation | 5 | MEDIUM |
| Accessibility & Polish | 10 | MEDIUM |
| AppKit Specific | 6 | LOW-MEDIUM |

## Key Features

- **iOS 17+ APIs**: `Spring`, `PhaseAnimator`, `KeyframeAnimator`, `scrollTransition`, `visualEffect`, `sensoryFeedback`
- **Web-to-SwiftUI mappings**: Concept translation from Framer Motion/CSS to SwiftUI
- **Production-ready code**: Each rule includes incorrect vs. correct examples
- **AppKit coverage**: 6 dedicated macOS rules for Core Animation
- **Accessibility**: Rules for `accessibilityReduceMotion` support

## Installation

Install using Vercel's [add-skill](https://github.com/vercel-labs/add-skill) CLI:

```bash
# Install the skill
npx add-skill emilkowal-animations-swift

# Install globally (across all projects)
npx add-skill pproenca/dot-skills --global
```

### Supported Agents

Skills are installed to agent-specific directories:
| Agent | Installation Path |
|-------|------------------|

## Skill Structure

```
skills/.experimental/emilkowal-animations-swift/
├── SKILL.md                    # Main overview and quick reference
├── metadata.json               # Skill metadata
├── assets/templates/
│   └── _template.md            # Rule template
└── references/
    ├── _sections.md            # Category definitions
    ├── ease-*.md               # 10 easing rules
    ├── timing-*.md             # 5 timing rules
    ├── props-*.md              # 7 property rules
    ├── transform-*.md          # 7 transform rules
    ├── gesture-*.md            # 14 gesture rules
    ├── transition-*.md         # 10 transition rules
    ├── scroll-*.md             # 6 scroll rules
    ├── strategy-*.md           # 5 strategy rules
    ├── polish-*.md             # 10 polish rules
    └── appkit-*.md             # 6 AppKit rules
```

## References

Based on:
- [Emil Kowalski's Animation Principles](https://emilkowal.ski/ui)
- [animations.dev](https://animations.dev/)
- [Apple Human Interface Guidelines - Motion](https://developer.apple.com/design/human-interface-guidelines/motion)
- [SwiftUI Animation Documentation](https://developer.apple.com/documentation/swiftui/animation)

## License

MIT
