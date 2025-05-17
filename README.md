The viewer.py is the one file of bempp-cl after modified. 

To use the efly-GUI version in Windows system (Win10/Win11 suggested), except the necessary environment setup, GMSH.exe programm (https://gmsh.info/bin/Windows/gmsh-4.13.1-Windows64) is necessary. Please download it and Adding the directory to the system PATH variable.

Procedure for adding the system PATH variable:

1. Open the Start Menu, search for "Environment Variables", and click on "Edit the system environment variables".

2. In the System Properties window, click the "Environment Variables..." button.

3. Under "System variables", find and select the Path variable, then click Edit.

4. Click "New" and enter the full path to the program's executable directory (e.g., C:\Program Files\YourApp\bin).

5. Click OK to close all dialogs.

6. Restart any open command prompts or restart your computer to apply the changes.

==========================================ATTENTION=====================================
\Lib\site-packages\bempp\api\external\viewers.py

To launch GMSH.exe as external programm successfully, the viewer.py has to be substituted by the modified one provided in the folder. The above path (\Lib\site-packages\bempp\api\external\viewers.py) is where the viewer.py should be placed.




