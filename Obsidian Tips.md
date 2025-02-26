# Obsidian Tips
## 1 Callouts
Some of the niche use cases and pretty are the Callouts. The Callout hints are **Case Insensitive**.

### 1.1 Available Callouts
- Note
- Abstract, Summary, TLDR
- Info
- Todo
- Tip, Hint, Important
- Success, Check, Done
- Question, Help, FAQ
- Warning, Caution, Attention
- Failure, Fail, Missing
- Danger, Error
- Bug
- Example
- Quote, Cite

***

```markdown
> [!NOTE] General Notes
> Any general note can be written here
```

> [!NOTE] General Notes
> Any general note can be written here

***

> [!Abstract]- Abstract, Summary, TLDR
> An abstract of a lengthy note

> Aliases: `summary`, `tldr`

***

> [!Info]- Info
> Any information somewhere

***

> [!Todo]- Todo
> A section for containing all the todos

***

> [!Tip]- Tip, Hint, Important
> Any hint somewhere

> Aliases: `hint`, `important`

***

> [!Abstract]- Success, Check, Done
> Any success note with green color

> Aliases: `check`, `done`

***

> [!Question]- Question, Help, FAQ
> An abstract of a lengthy note

> Aliases: `help`, `faq`

***

> [!Warning]- Warning, Caution, Attention
> A Warning Message

> Aliases: `caution`, `attention`


***

> [!Failure]- Failure, Fail, Missing
> A red failed box

> Aliases: `fail`, `missing`

***

> [!Danger]- Danger, Error
> An alert for danger

> Aliases: `error`

---

> [!Bug]- Bug
> A Bug note

***

> [!Example]- Example
> Example Note Section

***

> [!Quote]- Quote, Cite
> A quote of some person

> Aliases: `cite`

***

### 1.2 Foldable Callouts
By adding a plus (+) or a minus (-) directly after the type identifier a callout could be foldable.

#### 1.2.1 Collapsed Callouts
```markdown
> [!FAQ]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.
```

> [!faq]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

#### 1.2.2 Expanded Callouts
```markdown
> [!FAQ]+ Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.
```

> [!FAQ]+ Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

### 1.3 Nested Callouts
```markdown
> [!QUESTION] Can callouts be nested?
> > [!TODO] Yes!, they can.
> > > [!EXAMPLE]  You can even use multiple layers of nesting.
```

> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.

***
More on Callouts: https://help.obsidian.md/Editing+and+formatting/Callouts
***
## 2 Column Selection
```
Alt + Shift + <Click>
Alt + Shift + Drag
```

## 3 Exclude Excalidraw Files from Search
1. Get to **Settings** (<kbd>Ctrl</kbd> + <kbd>,</kbd>)
2. Choose **Files and Links**
3. **Excluded Files** (Manage)
4. Add these RegEx (Regular Expression) patterns
```regex
/(.excalidraw)/
/.excalidraw/
```
## 4 Tutorial
- [Cool **Obsidian Vaults**](https://www.reddit.com/r/ObsidianMD/comments/wxrtup/how_can_i_check_out_some_really_cool_obsidian/)
