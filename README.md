# PROG2007 – Lecture 4 Code Examples

Runnable Jetpack Compose examples for each slide in Lecture 4 ("Android Lifecycles and Software Architecture").

## How to use

Each folder contains a complete `MainActivity.kt` for one slide. To try one out, paste the whole file over your own `MainActivity.kt` in a Compose project (Minimum SDK 26+), then Run it.

Slides 20 and 24 also require the ViewModel-Compose dependency — add `implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.11.0")` to your module's `build.gradle.kts` and sync before running those two.

## Slides

| Slide | Topic | Code |
|---|---|---|
| 10 | Activity Lifecycle in Code | [slide-10-activity-lifecycle-in-code](./slide-10-activity-lifecycle-in-code) |
| 12 | The Problem: Data Lost on Rotation | [slide-12-data-lost-on-rotation](./slide-12-data-lost-on-rotation) |
| 20 | View and ViewModel in Code | [slide-20-view-and-viewmodel-in-code](./slide-20-view-and-viewmodel-in-code) |
| 24 | Repository in Code | [slide-24-repository-in-code](./slide-24-repository-in-code) |
