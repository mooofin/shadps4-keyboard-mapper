

# ShadPS4KeyMapper Project Structure

---

# ShadPS4KeyMapper Project Structure

## Directory Structure

### `/include` - Header Files

- **`/core`**
    - `KeyboardMapping.h` - Main mapping class
    - `ControllerButton.h` - Controller button definitions
    - `ConfigManager.h` - Configuration file manager
- **`/ui`**
    - `MainWindow.h` - Main application window
    - `KeyboardVisualizer.h` - Visual keyboard representation
    - `ControllerVisualizer.h` - Visual controller representation
    - `ProfileManager.h` - Profile management UI


### `/src` - Source Files

- **`/core`**
    - `KeyboardMapping.cpp`
    - `ControllerButton.cpp`
    - `ConfigManager.cpp`
- **`/ui`**
    - `MainWindow.cpp`
    - `KeyboardVisualizer.cpp`
    - `ControllerVisualizer.cpp`
    - `ProfileManager.cpp`
- `main.cpp` - Application entry point


### `/resources` - Resource Files

- **`/images`**
    - `keyboard.png`
    - `controller.png`
    - `/buttons` - Button images
- **`/styles`**
    - `dark_theme.css` - CSS stylesheets
- **`/profiles`**
    - `default.json`
    - `/games` - Game-specific profiles


### `/tests` - Unit Tests

- `/core_tests`
- `/ui_tests`


### `/docs` - Documentation

### Root Files

- `CMakeLists.txt` - CMake build configuration
- `.gitignore`
- `README.md`

<div>⁂</div>

