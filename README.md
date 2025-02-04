# Expo CLI Android Build Failure: AGP Version Conflict

This repository demonstrates a common issue encountered when building Android apps with the Expo CLI: an incompatibility between the Android Gradle Plugin (AGP) version used by Expo and the versions required by project dependencies.

## Problem

The Expo build process fails with error messages indicating version conflicts related to the AGP. This prevents successful generation of the Android APK.

## Solution

The solution often involves adjusting the AGP version within the Expo build configuration or managing dependency versions to ensure compatibility.  This may require manually configuring the Android build process or using specific Expo SDK versions that resolve the conflict. Detailed steps are provided in `expoBugSolution.js`

## Reproduction

To reproduce the error, refer to `expoBug.js`. This file contains code simulating a project setup that could trigger the AGP version conflict. Note that the exact reproduction will depend on the specific dependencies used and their AGP requirements.