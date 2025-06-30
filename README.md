# WeightTrack App

## Project Summary

The WeightTrack App is a lightweight Android application designed to help users track their daily weight, monitor progress, and stay motivated. The core user need this app addresses is the ability to easily log weight over time and set personal goals in a simple, intuitive interface. An optional SMS feature notifies users when their goal is achieved, providing a motivational boost. The app was developed with user-centered design principles in mind and focuses on clarity, simplicity, and accessibility.

## UI Design and Features

To support user needs, the app includes:
- A main activity for entering and updating daily weight records
- A grid-based view to display past entries clearly
- A goal-setting screen with optional SMS notifications
- A clean, readable layout with appropriate text sizes and contrast

The UI was designed with accessibility in mind by following Android’s design guidelines and emphasizing usability for users of all ages. Features like straightforward navigation, labeled inputs, and confirmation dialogs help ensure a user-centered experience. The design evolved from wireframes created in Project Two and was refined during implementation in Project Three.

## Development Process

Development began with a modular architecture, starting with one functional activity and gradually adding more features. I used Android Studio’s layout tools and component previews to ensure design fidelity, and I frequently refactored components for reuse. Debugging tools built into Android Studio were used in place of print-based debugging to improve efficiency and precision. These strategies will be helpful for future projects, especially when building scalable apps.

## Testing and Validation

I tested each screen after implementation by simulating user actions through the emulator. I also tested the SMS feature on a physical device to validate real-world permission handling. Testing was critical for ensuring each component behaved as expected and helped uncover issues such as missing layout constraints or deprecated API warnings early in development.

## Innovation and Challenges

One challenge I faced was designing a simple way to notify users via SMS while preserving privacy and minimizing required permissions. To solve this, I added SMS as an opt-in feature with clear labeling and request dialogs. I also had to innovate by improving the layout flow between activities to prevent data loss and make record editing more intuitive.

## Highlights and Strengths

A key success was the app’s grid-based view. It clearly displays user data and allows for smooth editing and deletion of records. This component demonstrates my understanding of user experience design, Java-based Android development, and lifecycle-aware coding practices.
