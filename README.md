# Expo Camera Freeze on Android

This repository demonstrates a bug encountered when using the Expo Camera API on certain Android devices. The camera preview intermittently freezes or displays a black screen, without providing any specific error messages in the console.  This makes it difficult to diagnose and resolve.

The `bug.js` file contains a minimal reproduction of the issue.  `bugSolution.js` (if a solution is found) will offer a workaround or fix.  Contributions are welcome!

## Reproduction Steps

1. Clone the repository.
2. Run `expo start`.
3. Observe the camera preview on an Android device.  The freeze or black screen may occur after a variable amount of time.

## Potential Causes

- Issues with Android device-specific camera drivers or hardware acceleration.
- Memory leaks or resource exhaustion within the Expo Camera component. 
- Timing issues or race conditions in the interaction between the native and Javascript components.

## Solution (if applicable)

[Describe solution here if found, otherwise state that a solution hasn't yet been identified]