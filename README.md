# Fitness App

A React Native application for tracking fitness workouts, built with Expo.

## Project Structure

The project follows a standard Expo Router structure:

```
.
├── assets/              # Static assets like icons and splash screens
├── src/
│   ├── app/             # Expo Router routes/screens
│   │   ├── _layout.tsx  # Main layout component
│   │   ├── index.tsx    # Home screen
│   │   └── workout/     # Workout related screens
│   ├── components/      # Reusable UI components
│   │   ├── general/     # General purpose components
│   │   ├── logger/      # Components for workout logging
│   │   └── workouts/    # Components for displaying workouts
│   ├── constants/       # Project constants (e.g., Colors)
│   ├── data/            # Static data (e.g., dummy workouts, exercises list)
│   ├── db/              # Database interaction logic (schemas, connections)
│   ├── services/        # Business logic for data handling
│   ├── store/           # State management setup (e.g., Zustand, Redux)
│   ├── types/           # TypeScript type definitions
│   └── utils/           # Utility functions
├── .gitignore
├── app.json             # Expo configuration
├── babel.config.js      # Babel configuration
├── bun.lock             # Bun lock file
├── package-lock.json    # npm lock file (consider removing if using Bun exclusively)
├── package.json         # Project dependencies and scripts
└── tsconfig.json        # TypeScript configuration
```

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```
2.  **Install dependencies:**
    ```bash
    bun install
    ```
3.  **Run the app:**
    ```bash
    npx expo start
    ```
    Follow the instructions in the terminal to open the app on a simulator/emulator or a physical device using the Expo Go app.

## Key Features (Inferred from Structure)

- **Workout Listing:** Displays a list of workouts.
- **Workout Details:** Shows details for a specific workout.
- **Workout Logging:** Allows users to log exercises and sets during a workout session.
- **Exercise Selection:** Provides a way to select exercises to add to a workout.
- **Data Persistence:** Likely uses a local database (inferred from `src/db`) to store workout data.

## Further Development

- Add detailed documentation for each component and function.
- Implement state management more thoroughly if needed.
- Add user authentication.
- Expand testing coverage.

_(Note: This README is based on the initial project structure. Please update it as the project evolves.)_
