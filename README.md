# Packager

 Packages Python scripts to distrubute easily.
 Instead of sending a sketchy looking folder full of dlls,
 now you only need the .pkg and something to run it.

## Creating a Package

```bash
Usage: create_package <input python script>
```

## Running a package

### Normal

Right click the file and click open with => Choose another app
Check "Always use this app to open .pkg files"
Click "More apps" => Look for another app on this pc => Navigate to this repo and select dist/run_package.exe as the application.

You can also just drag and drop the pkg on the executable (aka. Open with)

### From Cmd

```bash
Usage: run_package <.pkg file>
```
