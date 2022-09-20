from raylib import *
from raylib.colors import (
    RAYWHITE,
    LIGHTGRAY,
)


# ------------------------------------------------------------------------------------
# Program main entry point
# ------------------------------------------------------------------------------------
def main():
    screenWidth = 800
    screenHeight = 450

    InitWindow(screenWidth, screenHeight, b"raylib python cffi C API basic example")

    SetTargetFPS(60)  # Set our game to run at 60 frames-per-second
    # ------------------------------------------------------------------------------------

    # Main game loop
    while not WindowShouldClose():
        # Update
        # ----------------------------------------------------------------------------------
        # TODO: Update your variables here
        # ----------------------------------------------------------------------------------

        # Draw
        # ----------------------------------------------------------------------------------

        BeginDrawing()

        ClearBackground(RAYWHITE)

        DrawText(b"Congrats! You created your first window!", 190, 200, 20, LIGHTGRAY)

        EndDrawing()
        # ----------------------------------------------------------------------------------

    # De-Initialization
    # --------------------------------------------------------------------------------------
    CloseWindow()  # Close window and OpenGL context
    # --------------------------------------------------------------------------------------


if __name__ == '__main__':
    main()
