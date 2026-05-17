# audio-reactive-sprites
Audio-reactive sprite system for retro music visualizations using stem-driven character animation and palette-based rendering.

Music is split into stems, and each stem controls a sprite-based cat character. The visuals are built from processed footage of real cats, converted into low-resolution sprite animations with palette-based styling and retro UI overlays.

The goal is to build a simple pipeline that turns recorded music into a reactive visual system, where each instrument is represented by a character.

---

## structure

- `footage/` raw video source material (cats, performance, references)
- `stems/` separated audio tracks used for analysis and triggering
- `cat_frames/` extracted image sequences from footage
- `sprite_sheets/` cleaned animation assets (idle, sing, peak, etc.)
- `blender/` 3D props and render scenes
- `scripts/` audio analysis and automation tools
- `renders/` intermediate animation tests
- `composites/` final exported videos

---

## current status

prototype phase. building first working loop with, one cat, one stem, and basic amplitude-based animation switching to make the simple retro UI overlay
