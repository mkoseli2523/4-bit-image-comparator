# 4-bit Image Comparator

This project implements a high-speed 4-bit digital image comparator using full-custom design techniques. The comparator operates across dual-voltage domains (1.1V core / 1.8V I/O) and is designed for 2.4 GHz operation across multiple process corners.

## Repository Contents

- `implementation/` – Contains all schematics and layout views developed using Cadence Virtuoso.
- `project_report.pdf` – Includes detailed descriptions of the design methodology, implementation steps, simulation setup, and final performance results.

## Summary

The design includes custom registers, level shifters, parallel-serial interface logic, and off-chip drivers. Post-layout timing and functionality were verified using HSPICE simulations.

For full technical details, please refer to `project_report.pdf`.
