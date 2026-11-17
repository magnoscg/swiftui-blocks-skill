# SwiftUI Blocks skill

A skill that lets your coding agent find a component in
[SwiftUI Blocks](https://swiftuiblocks.dev), a catalog of copy-paste SwiftUI
components for iOS 18 through iOS 27, and add its file to your project.

This repository only distributes the skill, so installing it downloads a few
kilobytes. The catalog, the skill's source and the issues live in
[magnoscg/swiftui-blocks](https://github.com/magnoscg/swiftui-blocks).

## Install

Any agent that reads skills, with the
[skills](https://www.npmjs.com/package/skills) CLI:

```sh
npx skills add magnoscg/swiftui-blocks-skill
```

Claude Code, as a plugin:

```sh
claude plugin marketplace add magnoscg/swiftui-blocks-skill
claude plugin install swiftui-blocks@swiftuiblocks
```

Then ask your agent for what you need: *add a like button that bursts into
hearts*. More options at <https://swiftuiblocks.dev/install/>.
