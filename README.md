# angular_corrections

Project to produce post-processed corrections to in-flight the camera position of a Phantom 4 Pro drone, being used for commercial photogrammetry.

The project has two aspects:
- Automatically extract and store the angular information (Pitch, Roll and Yaw of drone) from the EXIF data of the .JPG files from each flight

- Use this data to correct the camera position of processed GPS flight track
