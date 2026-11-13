# FyraInput SDK packages

Public Windows x64 user-mode SDK source packages. These folders contain the existing SDK and its licenses; no kernel driver, activation secret or installer is included.

- [Native SDK source and recipes](https://github.com/TitanCSA/sdk-packages/blob/main/projects/FyraInput/packaging/native/README.txt)
- [Registry status](SDK-PUBLICATION.md)

Downloadable release artifacts do not imply publication on a central package registry.

<!-- central-sdk-packages:start -->
## Paquets et installation

Les sources, licences, guides API et exemples sont regroupes dans [le depot SDK dedie](https://github.com/TitanCSA/sdk-packages/tree/main/projects/FyraInput). Choisis le paquet a installer puis execute sa commande dans son dossier.

| Registre | Paquet | Installation / utilisation |
| --- | --- | --- |
| vcpkg | `fyrainput` | `vcpkg install fyrainput:x64-windows` |
| Conan | `fyrainput` | `conan install --requires=fyrainput/0.1.0 -r titancsa --build=missing -s compiler.cppstd=17` |
| NuGet | `FyraInput.Native` | `Install-Package FyraInput.Native -Version 0.1.0` |
| NuGet | `FyraInput.SDK` | `dotnet add package FyraInput.SDK --version 1.0.0` |
| PyPI | `fyrainput` | Commande prevue apres publication : `python -m pip install fyrainput==1.0.0` |
| Conda | `fyrainput` | `conda install --override-channels -c https://raw.githubusercontent.com/TitanCSA/sdk-packages/089bc73095aa8eda89bacbe10d0b9e58394b0207/conda-channel -c conda-forge fyrainput` (canal TitanCSA) |
| crates.io | `fyrainput` | `cargo add fyrainput@1.0.0` |
| npm | `fyrainput` | `npm install fyrainput@1.0.0` |
| Maven Central | `io.github.titancsa:fyrainput` | `io.github.titancsa:fyrainput:1.0.0 (pom.xml / Gradle)` |
| JitPack | `com.github.TitanCSA:FyraInput-SDK` | `com.github.TitanCSA:FyraInput-SDK:java-sdk-v1.0.0 (avec le depot JitPack)` |
| Go Modules | `github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules` | `go get github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules@v1.0.0` |
| pkg.go.dev | `github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules` | `Documentation : https://pkg.go.dev/github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules@v1.0.0` |
| PowerShell Gallery | `fyrainput` | `Install-Module FyraInput -RequiredVersion 1.0.0 -Scope CurrentUser` |
| pub.dev | `fyrainput` | `dart pub add fyrainput:1.0.0` |
| RubyGems | `fyrainput` | `gem install fyrainput -v 1.0.0` |
| Packagist | `fyrainput` | Commande prevue apres publication : `composer require titancsa/fyrainput:1.0.0` |

Pour vcpkg et Conan, configure d abord le registre TitanCSA avec [le guide complet](https://github.com/TitanCSA/sdk-packages/tree/main/projects/FyraInput/README.md). Le guide explique aussi Maven/Gradle, les prerequis et le chargement des DLL. Les pilotes/applications du produit sont installes separement. Les commandes marquees prevues ne sont pas encore disponibles.

Les anciens imports Go et versions JitPack gardent leurs tags. Pour les anciennes archives SDK, utilise [les liens de remplacement](https://github.com/TitanCSA/sdk-packages/blob/main/release-assets/URL-MIGRATION.json).
<!-- central-sdk-packages:end -->
