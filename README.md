# Diwali Animation Studio

A Python + Pygame Diwali greeting animation with fireworks, glowing diyas, floating lanterns, rangoli artwork and a cinematic staged reveal.

## What's improved

The scene now builds gradually instead of showing every element at once:

1. Stars softly appear in the night sky.
2. Decorative festive lights fade in.
3. Floating lanterns enter the scene.
4. The rangoli floor decoration is revealed.
5. Diyas light up progressively as one group.
6. Fireworks begin, followed by the greeting title and message.

The fireworks have also been enhanced:

- Rockets launch from the bottom of the screen and travel mostly upward.
- Each rocket leaves a short-lived, glowing particle trail.
- Launches happen more frequently but remain staggered, creating continuous action without making every explosion happen at once.
- The Space-bar grand finale sends up additional rockets for a denser burst of fireworks.

Each visual layer uses a smooth fade-in, creating a more cinematic opening. The interactive controls and snapshot feature are retained.

## Requirements

- Python 3.9 or newer
- Pygame

Install Pygame:

```bash
python -m pip install pygame
```

## Run

Open a terminal in this folder and run:

```bash
python diwali_animation_ultimate.py
```

Add a personal signature:

```bash
python diwali_animation_ultimate.py --name "Your Name"
```

For slower computers, use low particle quality:

```bash
python diwali_animation_ultimate.py --quality low
```

## Controls

| Key / Action | Function |
|---|---|
| Left click | Create a firework at the clicked position |
| Space | Trigger the grand finale |
| P | Pause / resume animation |
| A | Toggle automatic fireworks |
| F | Toggle fullscreen |
| S | Save a PNG snapshot in `diwali_snapshots` |
| H | Show / hide help text |
| Esc | Exit |

## Notes

- All artwork is drawn procedurally with Pygame. No external images, fonts or audio files are required.
- The animation runs in a resizable window and scales to fit the display.
