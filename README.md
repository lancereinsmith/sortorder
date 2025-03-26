# SortOrder

A collection of XML configuration files for sorting medical imaging series based on anatomical region.

## Overview

This repository contains various XML configuration files that define series sorting rules for different anatomical regions in medical imaging. The configurations help organize and display imaging series in a consistent and predictable order.

## Anatomical Regions

The repository includes sorting configurations for the following anatomical regions:

- Ankle
- Elbow
- Foot
- Hand
- Knee
- Shoulder
- Wrist

Additionally, there is a:
- `blank.xml` - Template file for creating new configurations
- `mr.xml` - Default/generic configuration for MR studies

## Configuration Structure

Each XML file defines sorting rules with:
- Series description patterns for different views (axial, coronal, sagittal)
- Sort order preferences (typically INCREASING)
- Special handling for secondary captures and localizers

## Usage

These configuration files can be used with compatible medical imaging viewing software to automatically sort and arrange series in a consistent manner based on anatomical region and scanning plane.

## License

Please refer to the license file for usage terms.
