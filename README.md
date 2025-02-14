# Expo Android Build Error: Android SDK Version Mismatch

This repository demonstrates a common issue encountered when building Android apps using the Expo CLI: an incompatibility between the Android SDK version declared in the project and the version installed in your development environment.  The `buildError.js` file simulates the build process and demonstrates the resulting error. The solution, in `buildSolution.js`, shows how to resolve the mismatch using the Android SDK Manager or by adjusting project configurations to match available SDK versions.

**Problem:** The Expo build process fails because required Android SDK components are missing or incompatible with the project's specified SDK version.

**Solution:**  Verify that your Android SDK includes the required components and that your project's SDK version setting aligns with your installed SDK components. Use the Android SDK Manager to install, update, or manage Android SDK components.