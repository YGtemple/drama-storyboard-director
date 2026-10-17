<div align="right">

**[English](README.md)** · [简体中文](README.zh-CN.md)

</div>

# drama-storyboard-director

Turns a script into a shot list, in 15-second segments.

<sub>Skill · `SKILL.md` + references</sub>

---

## What it produces

Given a script, it outputs a shot table. Each row is a shot:

| Column | Content |
|---|---|
| Shot number | sequential within the segment |
| Duration | seconds — usually 3–8 for dialogue, shorter for reactions |
| Shot scale | wide, medium, close, extreme close |
| Camera | static, push in, pan, handheld |
| Content | what is visible and what happens |
| Dialogue | the line, if any, with performance direction |
| Sound | ambient and effects |

## Why 15-second segments

A short-form platform rewards a hook inside the first few seconds and a reason to keep watching at each boundary. Segmenting at 15 seconds forces a question at every boundary: what makes someone keep going past this point?

Scripts that read fine on the page fall apart here. That is the point of the exercise.

## The reference material

`references/` holds the craft notes the skill draws on — how shot scale carries emotion, when a static camera beats a moving one, how to compress exposition into a single visual.

## Layout

```
SKILL.md        the method
references/     craft notes
```

## Using it

Load `SKILL.md` into an agent that supports skill bundles, then hand it a script. The output is a table, not a render — the shots still have to be produced.

## License

MIT
