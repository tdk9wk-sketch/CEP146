Cep146 - Lab2

Group Members: Mohamed ali, Wen Xin Gao, Aidan Pacheco

Select a scenario
-Selected Scenario 3: Developing a desktop application - Develop a simple calculator app for windows and mac

Environment planning
Select an IDE: Eclipse
Java tooling out of box
Short form for common Java paradigms
Java debug options
Includes jpackage (Executable wrapper)

Language: Java

Tools needed:
Java Swing
Cross platform graphics library for window management
Decreases development time by having one codebase for all platforms
Executable Wrapper
Jpackage
Required to package as native application files
Cross platform packager (Windows, MacOS)

WiX
Required to run jpackage (Windows)
XCode CLI (MacOS)
Required to run jpackage

Hardware Requirements:
Minimum 8GB ram for both Windows and MacOS
X86_64 or aarch64 capable cpu 

Estimated Setup Time: 
Low setup time:
Low Complexity: Download the .exe file if on windows
		      Download the .app file if on mac


















Team Collaboration:

ESTIMATED TIME: 20 MINUTES

Step 1: Install Eclipse
	
	Go to https://www.eclipse.org/downloads

	Download the latest release of eclipse
	Upon opening the file, you will be shown a prompt. Press “Run”



Once it opens, select the “Eclipse IDE for Java developers”

Step 2: Install a JDK

Open the oracle website at OpenJDK 

Download the latest version of OpenJDK


Step 3: Install tools needed for jpackage
Windows:
	Install WiX toolset https://github.com/wixtoolset/wix3/releases
	

MacOS:
	Open the MacOS terminal

	Run the install command in terminal
		xcode-select –install

Step 3: Import JavaSwing into your code
	
	Ensure that JavaSwing is imported at the top of your code before packaging it

Step 4: Package your code
Windows
		In order to use Jpackage to create the .exe file
		Type the command into the CLI: 
jpackage -t (type) –app-version (version) –icon (/path/to/icon) -n (name) -d (output)

		Substitute (type), (version), (file path), (name) and (output) with:

(type): Windows “exe” MacOS “dmg”
(version):  version of application
(file path): copy the path from your finder
(name): name of application
(output) copy the output file location


HOW TO DOWNLOAD CALCULATOR APP
	
	Windows
		Locate the latest release of the .exe file and download it to your device
		ReleasesWindows
		
	MacOS
		Locate the latest release of the .dmg file and download it to your device
		ReleasesMacOS
