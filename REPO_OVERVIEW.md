# Android Workshop Content 2013 — Repository Overview

This repository is a training curriculum organized as session folders for an Android workshop from the Eclipse/ADT era (pre-Android Studio). Most sessions include:

- `Slides/` or `slides/` teaching material (`.ppt`, `.pdf`)
- `Example code/` with runnable sample projects
- Legacy Android project layout (`src/`, `res/`, `AndroidManifest.xml`, `project.properties`, `bin/`, `gen/`)

## Top-level structure

The root is organized by session numbers and day-grouped sessions:

- `Session 1-Java Basics`
- `Session 2-Introduction to Android`
- `Session 3-Installation and building simple app `
- `Session 4-Android Building Blocks`
- `Session 5- Android UI`
- `Session 6-Android App Resources`
- `Session 7-Android Data Storage`
- `Session 8-Android Media`
- `Session 9- Android WebView`
- `Session X-Publishing your App`
- `Session XI- HTML5 on Android`
- `Session XII-Version control`
- `Sessions of Day 3`
- `Sessions of Day 4`

## Session-by-session intent

- **Session 1 (Java Basics):** foundational Java language exercises before Android-specific topics.
- **Session 2 (Intro):** introductory lecture material.
- **Session 3:** first simple Android app setup/build walkthrough.
- **Session 4 (Building Blocks):** core Android components demos (Activities/Intents/UI basics).
- **Session 5 (UI):** largest practical set; many UI widgets/layout demos and small apps.
- **Session 6 (Resources):** resource usage, themes/styles, assets handling.
- **Session 7 (Data Storage):** persistence-focused samples (files/preferences/SQLite patterns).
- **Session 8 (Media):** media playback/recording and related UI examples.
- **Session 9 (WebView):** embedded web content examples.
- **Session X:** app publishing/distribution slide deck.
- **Session XI:** HTML5 on Android training examples/slides.
- **Session XII:** version-control session material (Git intro).
- **Sessions of Day 3/4:** day-based workshop bundles with extra slides/examples.

## What is notable technically

1. **Legacy Android build system**
   - Projects use ADT/Eclipse metadata and Ant-era files (`project.properties`, generated `gen/`, packaged `bin/` artifacts).

2. **Many checked-in generated/binary files**
   - This repo intentionally stores generated classes (`R.java`, `BuildConfig.java`), APK outputs, and images for training convenience.

3. **Teaching-first organization**
   - Content is optimized for classroom progression, not for a single production app.

## Quick inventory snapshot (generated locally)

Approximate file and project counts by session directory:

- Session 1-Java Basics: 61 files, 19 Java files, 0 Android projects
- Session 2-Introduction to Android: 1 files, 0 Java files, 0 Android projects
- Session 3-Installation and building simple app : 29 files, 3 Java files, 1 Android projects
- Session 4-Android Building Blocks: 111 files, 11 Java files, 6 Android projects
- Session 5- Android UI: 580 files, 39 Java files, 26 Android projects
- Session 6-Android App Resources: 61 files, 3 Java files, 2 Android projects
- Session 7-Android Data Storage: 175 files, 15 Java files, 8 Android projects
- Session 8-Android Media: 158 files, 11 Java files, 6 Android projects
- Session 9- Android WebView: 50 files, 4 Java files, 2 Android projects
- Session X-Publishing your App: 2 files, 0 Java files, 0 Android projects
- Session XI- HTML5 on Android: 96 files, 0 Java files, 0 Android projects
- Session XII-Version control: 1 files, 0 Java files, 0 Android projects
- Sessions of Day 3: 96 files, 19 Java files, 2 Android projects
- Sessions of Day 4: 8 files, 0 Java files, 0 Android projects

## How to navigate this repo effectively

- Start with session folder names as syllabus order.
- Open each session’s slide deck first, then corresponding `Example code/` projects.
- For runnable examples, target folders containing `AndroidManifest.xml`.
- Ignore `bin/` and `gen/` when studying source logic unless you need generated outputs.

