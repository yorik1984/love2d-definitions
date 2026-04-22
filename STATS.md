## File structure

```bash
library/
├─ love.d.lua            # Core module with global definitions and root namespace
╰─ love/                 # Directory containing all LÖVE submodules
    ├─ audio.d.lua       # Provides an interface to create noise with the user's speakers.
    ├─ data.d.lua        # Provides functionality for creating and transforming data.
    ├─ event.d.lua       # Manages events, like keypresses.
    ├─ filesystem.d.lua  # Provides an interface to the user's filesystem.
    ├─ font.d.lua        # Allows you to work with fonts.
    ├─ graphics.d.lua    # The primary responsibility for the love.graphics module is the drawing of lines, shapes, text, Images and other Drawable objects onto the screen.
    ├─ image.d.lua       # Provides an interface to decode encoded image data.
    ├─ joystick.d.lua    # Provides an interface to the user's joystick.
    ├─ keyboard.d.lua    # Provides an interface to the user's keyboard.
    ├─ math.d.lua        # Provides system-independent mathematical functions.
    ├─ mouse.d.lua       # Provides an interface to the user's mouse.
    ├─ physics.d.lua     # Can simulate 2D rigid body physics in a realistic manner.
    ├─ sound.d.lua       # This module is responsible for decoding sound files.
    ├─ system.d.lua      # Provides access to information about the user's system.
    ├─ thread.d.lua      # Allows you to work with threads.
    ├─ timer.d.lua       # Provides an interface to the user's clock.
    ├─ touch.d.lua       # Provides an interface to touch-screen presses.
    ├─ video.d.lua       # This module is responsible for decoding, controlling, and streaming video files.
    ╰─ window.d.lua      # Provides an interface for modifying and retrieving information about the program's window.
```
