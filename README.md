# Integer-Interval Computation for LiDAR-Inertial Odometry

This repository contains the public implementation artifacts associated with the paper:

**ROAF: Real-time LiDAR-inertial Odometry Without Timestamp Casting Error Propagation for a UAV's Autonomous Flight**

## Status

This repository is prepared for the camera-ready release and will be updated after paper acceptance.

## Scope

This repository is intended to support the cross-framework portability results reported in the paper.

The released content focuses on the integer-based interval computation strategy applied to existing open-source LiDAR-inertial odometry frameworks.

## What is included

This repository will provide:

- migration notes for the integer-based interval computation strategy
- patch files for the modified timestamp representation and interval computation path
- instructions for applying the patches to the upstream frameworks
- minimal reproduction details for the portability experiments reported in the paper

## What is not included

This repository does not include:

- the full ROAF system
- a standalone release of the complete upstream frameworks
- commercial project components related to ROAF

## Supported upstream frameworks

The released patch-based migration materials correspond to the following frameworks used in the paper:

- Point-LIO
- FAST-LIVO2
- SuperLoc

## License notice

This repository distributes patch-based migration materials and documentation only.

The original framework source code is not redistributed here. Licenses for the upstream projects remain governed by their respective official repositories.

## Paper

Bibliographic information will be updated after publication.

## Contact

For questions about this repository, please open an issue.
