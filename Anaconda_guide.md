
# Anaconda Setup and Virtual Environment Management
you could follow this youtube link Visit [youtube.com](https://www.youtube.com/watch?v=WUeBzT43JyY) for installation guide alternatively

This guide will walk you through installing Anaconda and setting up a virtual environment for your projects.
## Installing Anaconda

1. **Download Anaconda**: Visit [anaconda.com](https://www.anaconda.com/products/individual) and download the appropriate Anaconda Installer for your operating system.

2. **Install Anaconda**:
    - **Windows**: Run the `.exe` file and follow the on-screen instructions.
    - **macOS**: Open the `.pkg` file and follow the on-screen instructions.
   
3. **Complete the Installation**: Use the default installation settings unless you have specific preferences.

## Creating a Virtual Environment

### Using Anaconda Navigator

1. **Launch Anaconda Navigator**: Find Anaconda Navigator in your applications and open it.
2. **Create an Environment**: Navigate to the "Environments" tab, click "Create", name your environment, select the Python version, and click "Create".

### Using Anaconda Command Line

1. **Open Anaconda Prompt (Windows)** or terminal (macOS/Linux).
2. **Create Environment**: Execute `conda create --name your_environment_name python=3.x`, where `.x` is the Python version you want.
3. **Activate Environment**: Run `conda activate your_environment_name`.

Replace `your_environment_name` with your chosen environment name for instance `gymnasium_env`
## Installing Additional Packages

- With the environment activated, install packages using `pip install package_name` example `pip install gymnasium`

## Managing Environments

- **Deactivate Environment**: Run `conda deactivate` to exit the active environment.

---
