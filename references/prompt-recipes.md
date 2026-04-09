# Prompt Recipes

Use this file when the user needs examples, stronger prompting structure, or a concrete starting point for a motion brief.

## Prompting Defaults

- Be explicit about timing.
- Mention fps when smoothness matters.
- Describe motion behavior, not only final layout.
- Use a recognizable visual reference when it clarifies tone.
- Break large videos into scenes before implementation.
- For Remotion output, ask for full composition setup, duration, and fps.

## Common Failure Fixes

- Missing composition setup:
  Ask for root composition wiring and explicit duration / fps.
- Wrong duration:
  State both seconds and total frames.
- Everything animates at once:
  Stagger each beat with explicit time windows.
- Motion feels robotic:
  Ask for spring animation or easing.
- Prompt is overloaded:
  Split the video into scenes, generate scenes, then combine.

## Recipe Starters

### Product Demo

App feature showcase:

```text
Create a 15-second product demo video showing a mobile app mockup in an iPhone frame with a dashboard UI inside. The phone slides in from the right, then highlights 3 features one by one with animated callout boxes. Use a gradient background from #667eea to #764ba2. Modern, clean aesthetic.
```

SaaS dashboard demo:

```text
Create a 20-second screen-recording-style video showing a SaaS dashboard. Start zoomed out on the full interface, then smoothly zoom into the analytics section. Add a cursor that moves naturally and clicks the Export button. Include a subtle drop shadow on the browser mockup.
```

Before / after comparison:

```text
Create a 10-second split-screen comparison. The left side shows Before with a cluttered UI mockup, the right side shows After with a clean UI. A vertical line sweeps from left to right revealing the transformation. Add labels with a smooth fade-in.
```

### Social Clip

Quote card animation:

```text
Create a 6-second Instagram-style quote video. Display the text "Ship fast, learn faster" with a typewriter animation. Add a subtle gradient background that slowly shifts colors. Include a small avatar circle in the corner that pops in at the end. 1080x1080 dimensions.
```

Stats counter:

```text
Create an 8-second video with an animated number counter going from 0 to 10,000. Add a plus symbol after the number and text below saying "Happy Users". Use spring animation for a satisfying bounce when it reaches the final number. Dark mode aesthetic.
```

### Explainer / Tutorial

Step-by-step walkthrough:

```text
Create a 30-second explainer video with 3 steps. Each step gets 8 seconds: Step 1 "Install the CLI" with a terminal icon, Step 2 "Run the command" with a code snippet animation, Step 3 "Deploy" with a rocket icon. Transitions should be smooth slides from the right. Include step numbers 1, 2, and 3 in circles.
```

Code snippet animation:

```text
Create a 12-second video showing code being typed in a code editor mockup. The code should be: const greeting = "Hello, world!"; console.log(greeting); Use syntax highlighting, with strings in green and keywords in purple. Add a blinking cursor and line numbers.
```

### Marketing Motion

Logo reveal:

```text
Create a 5-second logo reveal. Start with particles scattered across the screen, then have them converge to form the text "ACME". Add a subtle glow effect when fully formed. Black background.
```

Feature list animation:

```text
Create a 15-second video listing 5 features. Each feature flies in from the left with a checkmark icon, then stacks vertically. Features: Lightning fast, Secure by default, Easy setup, Great docs, 24/7 support. Make the motion feel rhythmic even without actual sound.
```

### Data / Typography

Data visualization:

```text
Create a 12-second video with an animated bar chart. Start with empty bars, then grow them to these values: Jan 40%, Feb 65%, Mar 80%, Apr 55%. Use a staggered animation so each bar grows one after another. Include axis labels and a title "Q1 Performance".
```

Text transition sequence:

```text
Create a 10-second video that cycles through 4 words: Build, Ship, Learn, Repeat. Each word scales from 0.5 to 1, holds briefly, then blurs out as the next word comes in. Use a bold, modern font with a centered layout.
```

## Better Prompt Upgrades

Upgrade vague prompts by adding:
- total duration
- fps
- scene order
- timing windows
- motion verbs such as slide, sweep, scale, blur, pop, stagger
- brand palette and typography cues
- output format such as square, landscape, vertical, or transparent
