# Python Install for Windows

![Python](https://python.tutorials24x7.com/uploads/2020-06-20/banner/tutorials24x7-install-python-3-8-on-windows-10-banner.jpg)

1. **Download Python Installer**: 
   - Go to the [official Python website](https://www.python.org/) and navigate to the Downloads section.
   - Click on the latest version of Python for Windows.
   - Choose the installer that corresponds to your system architecture (32-bit or 64-bit).

2. **Run the Installer**:
   - Once the installer is downloaded, double-click on it to run it.
   - You may see a security warning, click "Yes" or "Run" to proceed.

3. **Install Python**:
   - The installer will open.
   - Check the box that says "Add Python.exe to PATH".
   - Click on the "Install Now" button.
     
     ![](https://github.com/SalmanMurtazaMinhas/python-install-for-windows/assets/139884020/8aceb385-12a3-4e1e-a89a-2f3bd6effc79)

4. **Wait for Installation**:
   - The installer will now install Python on your system. This may take a few minutes.

5. **Verify Installation**:

  - Once the installation is complete, open the terminal and type:
    ```sh
    python --version
    ```
    You should see the installed Python version displayed.

 6.  **Install pip**:
   - In the terminal, use the following command to install or upgrade pip:
     ```bash
     python -m pip install --upgrade pip
     ```

7. **Verify pip Installation**:
   - After the installation or upgrade is complete, verify it by typing
   ```sh
    pip --version
    ```
    You should see the installed pip version displayed.

That's it! You've now installed Python and pip on your Windows system. You can use pip to install Python packages and manage dependencies for your projects.

## VsCode Extensions

Install the following extensions for VS Code:

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)

These extensions give us better support such as intellisense, autocomplete, and linting.


# Note

All lessons are written from the perspective of a Mac, so whenever a lesson instructs you to use `python3` as a command, please use `python` instead.

For example:

- Instead of `python3 --version`, you'll use `python --version`
