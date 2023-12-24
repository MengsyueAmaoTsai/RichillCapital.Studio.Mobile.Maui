# RichillCapital.Studio.Mobile

## Run Tests

```powershell
dotnet test --no-build /p:CollectCoverage=true /p:CoverletOutputFormat=lcov /p:CoverletOutput=../../coverage/lcov.info -- MSTest.Parallelize.Workers=5
```