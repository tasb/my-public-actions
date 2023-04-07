# My Public Actions

## Action: build-test-publish

Builds and runs unit tests for dotnet projects.

### Usage

```yaml
- uses: tasb/my-public-actions/build-test-publish@main
  with:
    mainProject: '<path for main project csproj>'
    testsProject: '<path for tests project csproj>'
```

## Action: build-dotnet

Builds a dotnet projects.

### Usage

```yaml
- uses: tasb/my-public-actions/build-test-publish@main
  with:
    mainProject: '<path for main project csproj>'
    testsProject: '<path for tests project csproj>'
```
