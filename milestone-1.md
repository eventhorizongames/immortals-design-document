---
layout: default
title: Milestone 1
---

# Milestone 1 Notes

## [In-Progress] Add Collision/Density

Using the graph on the server keep track of entities on a node.

The node can contain multiple entities, but only a single "dense" entity.

The server will have a single process, that single process will loop through the nodes. If their are more than one dense node on the server it will "push" an entity into a nearby available node.
