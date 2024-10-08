# To-Do List Application

This project is a basic To-Do List application that allows users to add, view, and manage tasks. The app features a splash screen with animations and uses fragments for task entry, all designed with a responsive user interface using ConstraintLayout.

## Features
1. **Splash Screen**: Displays the app’s logo with translate and scale animations. The logo moves from the top to the center and grows slightly in size.
2. **Main To-Do List Screen**: Displays a list of tasks, with each task represented by a `TextView`. Includes a Floating Action Button (FAB) for adding new tasks.
3. **Task Input Fragment**: A dedicated fragment for users to input task details (name and description) and save them.
4. **Responsive Design**: The app adapts to both portrait and landscape modes using ConstraintLayout for a consistent UI across different screen sizes.

## Design Guidelines
- All strings are located in `strings.xml`.
- All dimensions are defined in `dimens.xml`.
- All colors are specified in `colors.xml`.
- Consistent design across all screens in terms of color, fonts, and spacing.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/abubakar-shahid/To-Do-List-Application.git
    ```
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.
