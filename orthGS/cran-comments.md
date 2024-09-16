## R CMD check results

0 errors | 0 warnings | 1 note

* This is a revised submission of a new release.

* "If there are references describing the methods in your package, please
 	add these in the description field of your DESCRIPTION file ..."

 Currently there is not reference to be included.

* You write information messages to the console that cannot be easily
	suppressed ..." 

Tha has been fixed. Now the function speciesGS() returns a dataframe instead of printing the information into the console. 
Also, the function subsetGS() has been modified to use warning() instead of print(). The corresponding unit tests have been included.

* Please do not install packages in your functions, examples or vignette.
	This can make the functions,examples and cran-check very slow.

	This issue has now been fixed.

## Test environments

* local OS X install, R 4.4.0

* win-builder (devel and release)

* rhub linux (ubuntu-latest on GitHub)

* rhub macos (macos-13 on GitHub)

* rhub windows (windows-latest on GitHub)
