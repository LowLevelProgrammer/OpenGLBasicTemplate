# OpenGLBasicTemplate
## Prerequisites
Before you start building the project, ensure you have the following installed:
- [Visual Studio](https://visualstudio.microsoft.com/) for Windows Project
- [Python](https://www.python.org/downloads/) (Optional: If you want to use ResetName.py script)
- [Git](https://git-scm.com/)

## Steps to Build

### 1. Clone the Repository
Clone the project repository to your local machine using Git:
```bash
git clone https://github.com/LowLevelProgrammer/OpenGLBasicTemplate.git
```

### 2. Rename the Project (Optional)
You can rename the project name using the ResetName.py script<br>
*(Warning: Don't cd into the git repository directory yet)*
```bash
python OpenGLBasicTemplate\ResetName.py <new_name>
```

**If you dont want to use the ResetName.py script then delete the script file**<br>
**Else after running the script delete ResetName.py**
### 3. Generate Visual Studio Solution Files
- To generate project file for visual studio, first cd into the git repo directory
```bash
cd <new_name>
```

- Then run the GenerateSolutionFile.bat file
```bash
.\GenerateSolutionFile.bat
```
#### OR

Alternatively, you can manually run the script by double clicking the script file in the git repository

### 4. Remove the Reference to the Original Repository
Remove the remote reference to this original repository
```bash
git remote remove origin
```

### 5. Add Your Own Remote (Optional):
If you want to push your changes to your own remote repository, you can add your own remote using:
```bash
git remote add origin <url-to-your-remote-repository>
```