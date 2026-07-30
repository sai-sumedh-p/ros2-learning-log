# Phase 0 — Setup

## Day 1: ROS 2 Lyrical Luth Installation

- OS: Ubuntu 26.04 (Resolute)
- Installed ROS 2 Lyrical Luth (Desktop) via apt
- Fixed a Signed-By conflict between a pre-existing `ros2.sources` (deb822 format)
  and a manually added `ros2.list` — removed both and recreated cleanly
- Sourced ROS 2 in `.bashrc`
- Verified installation with `ros2 doctor --report`
- Ran the classic talker/listener demo across two terminals — confirmed pub/sub
  communication working correctly

### Key learnings
- ROS 2 uses DDS under the hood for node discovery and communication
- `ros2 run <package> <executable>` is the basic way to launch a node
- Ubuntu 26.04 ships with pre-configured ROS sources that can conflict with manual setup

### Next: Phase 1 — Core Concepts
- Nodes, topics, services, actions, parameters

