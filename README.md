## Angular 7 app

Running Angular 7 app without errors in 2023.

### Versions

* Local Angular: 7
* Global Angular CLI: 14.0.0
* Global Node: 14.21.3
* Global NPM: 6.14.18
* Global Python: python2.7
* Local Node-Sass: 4.14.1

### NPM Install Issues

```
gyp verb command configure []
gyp verb check python checking for Python executable "python2.7" in the PATH
gyp verb `which` failed Error: not found: python2.7

...

Building solution configuration "Release|x64".
MSBUILD : error MSB3428: Could not load the Visual C++ component "VCBuild.exe". To fix this, 1) install the .NET Framew
ork 2.0 SDK, 2) install Microsoft Visual Studio 2005 or 3) add the location of the component to the system path if it i
s installed elsewhere.  [D:\Angular-Training\Food-App\node_modules\@angular-devkit\build-angular\node_modules\node-sass
\build\binding.sln]
Done Building Project "D:\Angular-Training\Food-App\node_modules\@angular-devkit\build-angular\node_modules\node-sass\b
uild\binding.sln" (default targets) -- FAILED.

```

### Can Run ng build? - Yes! Without errors.

### Can Run ng serve? - Yes! Without errors.

### Can Run ng t? - Yes! Without errors.

#

### Dive in:

```
# Install dependencies
  npm i

# Run build
  npm run build

# Run Angular server (port 4200)
  npm run dev

```