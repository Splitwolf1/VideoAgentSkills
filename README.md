# Video Agent Pipeline

4-agent AI prompt pipeline for generating video content across Higgsfield, Seedance 2, and Kling.

## Pipeline

```
01 Creative Director → 02 Style Director → 03 Cinematographer → 04 Prompt Packager → Video Tools
```

## Agents

| # | Agent | Input | Output |
|---|---|---|---|
| 01 | Creative Director | Raw brief | Creative plan, emotional arc, hook strategy |
| 02 | Style Director | Creative Brief | Visual language spec, model routing |
| 03 | Cinematographer | Brief + VLS | Numbered shot list, 15 fields per shot |
| 04 | Prompt Packager | All 3 docs | Ready-to-use prompts per model |

## Files

- `VideoAgents.html` — visual reference with copy buttons, open in any browser
- `video-creative-director.md` — Agent 01 skill file
- `video-style-director.md` — Agent 02 skill file
- `video-cinematographer.md` — Agent 03 skill file
- `video-prompt-packager.md` — Agent 04 skill file

## Using with Claude Code

Copy the 4 `.md` files into your `.claude/commands/` directory:

```bash
# Mac/Linux
cp video-*.md ~/.claude/commands/

# Windows (run in Git Bash)
cp video-*.md ~/AppData/Roaming/Claude/commands/
```

Then invoke in any Claude Code session:
```
/video-creative-director
/video-style-director
/video-cinematographer
/video-prompt-packager
```

## Using the HTML file

Open `VideoAgents.html` in a browser. Each agent has a Copy button.
Paste the prompt into ChatGPT, Claude.ai, Gemini, or any other AI tool.

## Video Models

- **Higgsfield** — high-motion, physics, kinetic action, multi-subject chaos
- **Seedance 2** — photorealistic human movement, lifestyle, UGC authenticity
- **Kling** — character consistency, animation styles, close-up face detail

## Supported Styles

**Realism:** Cinematic, UGC/Native, Documentary, Noir
**World:** Historical/Period, Cyberpunk, Black Mirror/Near-Future
**Animation:** Disney/Pixar 3D, Studio Ghibli, Anime, Cubist/Abstract, Motion Graphics
**Director Mode:** Nolan, Fincher, Wes Anderson, A24
