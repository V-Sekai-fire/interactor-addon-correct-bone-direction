# interactor-addon-correct-bone-direction

A Godot 4 editor plugin that corrects the bone directions of imported skeletons and the bind poses of their meshes.

## Use

The plugin adds a scene post-import step. After a scene imports, it walks the scene, rewrites the rest pose of every skeleton it finds so each bone points along its chain, and adjusts the bind poses of the skeleton's meshes to match.

## Build and run

Copy the repository into a project's `addons/correct_bone_direction/` directory, the path its scripts load from, and enable the plugin in the project settings.

## Licence

MIT. See `LICENSE`.
