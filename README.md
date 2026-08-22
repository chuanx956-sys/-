# ComfyUI HahaCat MiniMax H3 Controlled Action Reference

This is a single ComfyUI custom-node package that bundles the HahaCat MiniMax H3 short-drama workflow helper nodes, commercial MiniMax H3 validation nodes, reserved VRAM node, storyboard/asset nodes, and action/expression reference nodes.

## Install

Clone or copy this folder into:

```text
ComfyUI/custom_nodes/ComfyUI-HahaCat-MiniMaxH3-ControlledActionReference
```

Then install optional requirements in the ComfyUI Python environment:

```bash
pip install -r requirements.txt
```

Restart ComfyUI after installation.

## Included Node Classes

- `MiniMaxH3FrameLengthCommercial`
- `MiniMaxH3OutputQCCommercial`
- `ReservedVRAMSetter`
- `MiniMaxH3ReferenceValidatorCommercial`
- `H3ActionSegmentConfig`
- `H3SegmentActionConfigSelector`
- `H3SegmentActionMediaSelector`
- `H3ActionReferencePrompt`
- `H3ActionCaptureSwitch`
- `H3FaceExpressionSegmentConfig`
- `H3FaceExpressionConfigSelector`
- `H3FaceExpressionPrompt`
- `H3ReferenceImageSwitch`
- `H3ReferenceAudioSwitch`
- `H3SegmentDurationSelector`
- `H3ActionFrameSynchronizer`
- `H3SafeFacialPartColoring`
- `H3SegmentActionImageSelector`
- `H3AssetPromptReader`
- `H3ScriptSkillInput`
- `H3SegmentProductionManager`
- `H3AssetLibrary`
- `H3StoryboardDirector`
- `H3ReferenceVideoPrompt`
- `H3ActionSubtitleGuard`

## Notes

- This package is intended for MiniMax H3 reference-to-video workflows in ComfyUI.
- Reference videos used for motion or expression should be clean whenever possible. Burned-in subtitles, watermarks, and UI text can leak into generation.
- The storyboard module includes its web extension and workflow template under `storyboard/web` and `storyboard/workflow_templates`.
