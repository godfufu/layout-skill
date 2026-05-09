# Features

## DWG / DXF Workflow

- Convert DWG to DXF locally with ODA File Converter.
- Fall back to CloudConvert when local conversion is unavailable.
- Render DXF files into high-resolution PNG previews.
- Keep customer drawings local when using the local converter.

## Visual Zone Picker

- Launches a local browser interface.
- Allows users to draw rectangular functional zones.
- Saves zone color, boundary, canvas coordinates, and source-image coordinates.
- Supports multiple zones with automatic color assignment.

## Guided Planning Data Collection

- Collects project name, address, and total area.
- Prompts for each zone's name, area, usage, and requirements.
- Exports structured YAML config for repeatability.

## PDF Planning Output

- Automatically crops CAD whitespace so the drawing fills the page.
- Chooses page direction from the actual drawing aspect ratio.
- Keeps zone names out of the drawing to avoid overlap.
- Uses colored overlays plus a legend and detail table.
- Separates plan view and detailed zone information into clean pages.

## AI Prompt Output

- Generates source-constrained master plan prompts.
- Generates zone-specific rendering prompts with position, scale, boundary, and adjacency context.
- Exports JSON, TXT, and Markdown.
- Exports a whole-plan AI reference map.
- Exports per-zone reference crop images.
- Marks prompts as reference-image required, because text-only prompts cannot guarantee layout fidelity.
- Includes model-specific usage notes for Midjourney, DALL-E, Stable Diffusion, and ControlNet workflows.
- Preserves the original footprint, walls, corridors, entrances, and zone placement while allowing materials, furniture, lighting, signage, activity, and atmosphere to change.
- Works with Midjourney, DALL-E, Stable Diffusion, and similar image tools.

## Agent Integration

- Includes a Claude/Codex skill definition.
- Skill metadata is optimized for DWG, DXF, CAD, zoning, PDF, and AI prompt search.
- Supports command-line usage and agent-driven workflows.

## Commercial Readiness

- Commercial source-available license.
- Public marketing materials.
- Private paid repository workflow.
- Release checklist and sales plan included.
