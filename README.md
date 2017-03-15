# Lib1
Example Repository for [GitDepend](https://github.com/GitDepend/GitDepend)

This is the lowest level repository.

## Building
To build this repository you must have Visual Studio 2015 installed.

Run `make.bat` to build the project. Nuget Packages will be available at `artifacts\NuGet\Debug`

## GitDepend Configuration

`GitDepend.json`

```json
{
  "name": "Lib1",
  "build": {
    "script": "make.bat",
    "arguments": ""
  },
  "packages": {
    "dir": "artifacts/NuGet/Debug"
  },
  "dependencies": []
}
```
