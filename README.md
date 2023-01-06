This project can be used to scaffold a prototypical .NET solution including file system layout and tooling. 

- `artifacts` - Build outputs go here. Doing a build.cmd/build.sh generates artifacts here (nupkgs, dlls, pdbs, etc.)
- `build` - Build customizations (custom msbuild files/psake/fake/albacore/etc) scripts
- `docs` - Documentation stuff, markdown files, help files etc.
- `lib` - Things that can **NEVER** exist in a nuget package
- `packages` - NuGet packages
- `samples` (optional) - Sample project or static mockups
- `src` - Main projects
- `tests` - Test projects
- `.editorconfig` - x-plat IDE settings
- `build.cmd` - Bootstrap the build for windows
- `build.sh` - Bootstrap the build for *nix
- `README.md and LICENSE` - Critical if you're OSS, if not ignore it
- `NuGet.config` - For control NuGet behavior and sources
