# Disassembler Samples
Some small samples to test mono disassembler (`monodis`) on.

# Building
Since the projects target both .NET Framework and .NET Core, I suggest using
`msbuild` instead of `dotnet`.
``` sh
$ msbuild /t:Restore
$ msbuild /t:Build
```