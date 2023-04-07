# Listed-VPM-Template
This repo was made real quick for personal use but feel free to use it too.<br>
This is the bare minimum to get a repo package listed in the Page you make from https://github.com/vrchat-community/template-package-listing to avoid having so much clutter.<br>

### Instructions
1- Use this template to make your own repository. Can be private but public later.
2- Replace the appropriate/example things in every file:
	- .git/release.yml - Just lines 7 to 11
	- package.json, CHANGELOG.md, LICENSE.md
	- Assembly Definitions file names AND 'Name' (click on it)
	- Documentation~/com.dreadscripts.example (File name too!)

3- Delete script folders, documentation, CHANGELOG and LICENSE if they're unused.<br>
4- Go to your listing repository and add the repo you made from this template to 'source.json' under 'githubRepos'.<br>
5- Done!

# WARNING
The (!) button for packages made from this repo won't work by default.<br>
For the .unitypackage to build properly with Github actions, you need to include the .meta files for the package.<br>
This is slightly customized to fit my liking with the naming and versioning.<br>
[Here's my VPM Listing!](https://vpm.dreadscripts.com/)