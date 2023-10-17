<!--
Copyright 2023-present K. S. Ernest (iFire) Lee
SPDX-License-Identifier: CC-BY-4.0
-->

# VSEKAI_material_mtlx

## Contributors

* K. S. Ernest (iFire) Lee, Godot Engine contributor, [contact info]

## Status

Draft

## Dependencies

Written against the glTF 2.0 spec.

## Overview

This extension proposes integrating MaterialX (MTLX) into the GLTF specification. MaterialX is an open standard for transfer of rich material and look-development content between applications and renderers. The primary use case is to allow more complex and versatile materials to be used in GLTF, enhancing the visual quality and realism of rendered objects.

## glTF Schema Updates

The `material` object will have an additional property `mtlx`, which is a URI to the MaterialX definition.

### JSON Schema

[Link to the JSON schema for the new extension properties.]

## Known Implementations

* Proposed for implementation in Godot Engine and three.js.

## Resources

* [Link to the GitHub issue discussing this proposal.]
* [Link to the PR in Godot Engine related to this proposal.]
