# xa-build-dependencies

Convert assemblies used to test Xamarin.Android into NuGets

To build:
```
cd src
dotnet pack --configuration Release
```

The resulting `.nupkg` will be in `/nupkg`.