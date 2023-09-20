# node-lifecycle-poc

This repository is a PoC intended to demonstrate node lifecycle hooks. This is an adaptation of the "github-lifecycle-*" pattern used within the puppet repository.

The idea is that we provide partner teams with a hooks that they can use to schedule work at different points of the node lifecycle. For example, if we intend to remove a node, the partner teams can specify pre- and post- node removal actions. Each partner team maintains their own hooks, which helps clarify ownership and responsibities across teams.
