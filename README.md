# Eris Epsilon PCB
Eris Epsilon is the 5th version of Duke AERO's SRAD flight computer ERIS.

## Usage
This year, we are switching to KiCAD for PCB design. Previous years have used Eagle. The Eagle files and datasheet for ERIS Delta are available in the Google Drive under `2024/2025 Aero>Avionics>Eris Delta`.

### KiCad Setup
To install KiCad see [here](https://www.kicad.org/)

### Git Workflow
#### Getting this project
1. Make sure you have Git installed
2. In the terminal, navigate to the directory where you want to have this project
* You can sometimes do so by opening the folder, right clicking, and clicking "open in terminal/open in powershell"
* Otherwise, navigate to the directory in your file explorer. Copy the path. Open terminal (Mac), cmd, or powershell (Windows) and enter `cd <directory`.
3. Run `git clone git@github.com:Duke-AERO-Team/eris-epsilon.git`

#### Making changes
##### You haven't made any changes yet
1. Run `git branch <change_title>`
2. Run `git switch <change_title>`
3. Make your changes
4. Run `git add .` or add each file you changed one by one
5. Run `git commit "description of your changes"
6. Run `git push --set-upstream origin <change_title>`
7. See "merging" below

##### Merging
In the past, I have been horrible with version control! No longer. To make your changes a part of the official schematic, you must make the changes in a separate branch, make a pull request, and have someone verify your changes before merging.
