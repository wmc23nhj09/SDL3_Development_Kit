# SDL3 Development Kit

A central collection of SDL3 headers, linker, and DLL files used across my projects.

## Purpose

This repository exists to provide a reusable SDL3 setup so projects do not need to repeatedly download and configure the same files.

## Contents

- SDL3 Headers
- SDL3 Libraries
- SDL3 Runtime DLLs
- Documentation

## Usage

This repository contains shared SDL3 development files used by my projects.

1. Clone this repository.
2. Point your project include path to `/include`.
3. Point your linker path to `/lib`.
4. Place required DLL files beside your executable.

## Structure

SDL3_Development_Kit
│
├── include/
│   └── SDL3 headers
│
├── lib/
│   └── linker files
│
├── bin/
│   └── runtime DLLs
│
└── docs/
