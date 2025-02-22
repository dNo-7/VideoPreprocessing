﻿# VideoPreprocessing
# Remove Silent Frames from Videos

This repository contains a Python script that automates the process of detecting and removing silent frames from videos using FFmpeg. Follow the steps below to set up FFmpeg and use the script.

## Steps to Set Up FFmpeg

1. **Download FFmpeg**  
   Download FFmpeg from the official [FFmpeg website](https://ffmpeg.org/).

2. **Extract FFmpeg**  
   Extract the downloaded ZIP file to a directory of your choice (e.g., `C:\ffmpeg`).

3. **Add FFmpeg to PATH**  
   Add the FFmpeg directory to your system's **PATH** environment variable.  
   - On Windows:
     1. Search for "Environment Variables" in the Start Menu.
     2. Click on "Edit the system environment variables."
     3. In the System Properties window, click on **Environment Variables**.
     4. Under **System Variables**, find the `Path` variable and click **Edit**.
     5. Add the path to your FFmpeg directory (e.g., `C:\ffmpeg\bin`).
     6. Click **OK** to save the changes.
   - On macOS/Linux:
     Add the following line to your `.bashrc` or `.zshrc` file:
     ```bash
     export PATH=$PATH:/path/to/ffmpeg/bin
     ```

4. **Verify the Installation**  
   Open a terminal or Command Prompt and run the following command:  
   ```bash
   ffmpeg -version
