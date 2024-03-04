# Python install for windows

![](https://analyticsindiamag.com/wp-content/uploads/2019/10/python-1-1600x901.jpg)

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

Install the following extension for vsCode:

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

Open the `main.py` file, vsCode will prompt you to install a few things such as:

- Linter, select `pylint`
- Formatter, select `autopep`

The python language extension gives us better support for the python language such as, intellisense, autocomplete and linting.


# Note
All lessons are tailored for Macs, so whenever a lesson instructs you to use "python3" as a command line command, please use "python" instead.

for example:

instead of `python3 --version` you'll use `python --version`
