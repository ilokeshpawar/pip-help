# pip-help
pip-help is a command line tool for temporarily installing packages.

## Problem:
- It often happens that for some tasks, you have to install a <package> on your system. During that process, you end up downloading many <dependent_packages> which you might not require once the task is finished.

- When you uninstall the <package> using pip, the process only uninstalls the <package> and not the <dependent_packages>.

- Although you have uninstalled the <package>, the <cache> and <dependent_packages> remain somewhere on your system, taking up memory.

## Solution:
- This tool aims to solve all the problems listed above.

## Installation Guide
- **STEP(1): Download the artifact containing the wheel from the actions tab in the repo [pip-help](https://github.com/Lokesh-pawar/pip-help).

- **STEP(2): Open the terminal in the directory containing the wheel, and install the **pip-help** package with the command: `pip install <wheel_name.whl>`.

- **STEP(3): Voila!!

## Getting Started
Currently, it provides support for installing and uninstalling a <package> (let's consider that the package name is "matplotlib") and its <dependent_packages>.

- Use the flag -h/--help for further information.

- Example usage (installing a package): `pip-help -i (or --install) matplotlib`

- Example usage (uninstalling a package): `pip-help -r (or --remove) matplotlib`

## PS:
- It can install and uninstall multiple packages in one go.