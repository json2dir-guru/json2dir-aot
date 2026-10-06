# json2dir-aot

[json2dir](https://github.com/alurm/json2dir) in C#, compiled with .NET 8 Native AOT (hand-written JSON parser, no NuGet packages).

```sh
dotnet publish -c Release -r linux-x64 -o out && out/json2dir < tree.json
```
