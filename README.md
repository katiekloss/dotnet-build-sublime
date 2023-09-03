# dotnet-build-sublime
Sublime Text build system for .NET Core projects

## Dependencies
- Any recent [.NET SDK](https://dotnet.microsoft.com/en-us/download)
- [ANSIescape package](https://packagecontrol.io/packages/ANSIescape) for colorful build output

## Etc
- A sample project file for .NET (paste into `your-project-name.sublime-project` in the root of your project):
```json
{
  "folders":
  [
    {
      "path": ".",
      "folder_exclude_patterns": ["bin", "obj"],
    },
  ],
}
```
