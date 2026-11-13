# SDK publication status

Current source layout and registry coverage. A GitHub download is distinct from publication on a central registry.

| Target | Status | Package / documentation |
| --- | --- | --- |
| CPP/vcpkg | published_custom_registry | fyrainput |
| CPP/conan | published_custom_source_index | [fyrainput](https://github.com/TitanCSA/sdk-packages/tree/089bc73095aa8eda89bacbe10d0b9e58394b0207/conan-index) [Source](packaging/native/) |
| CPP/nuget | account_email_confirmed_requires_matching_trusted_publishing_policy | FyraInput.Native |
| NET/nuget | built_verified_requires_trusted_publishing_policy | FyraInput.SDK [Source](FyraInput-NET-nuget/) |
| Python/pypi | built_fixture_and_production_verified | fyrainput [Source](FyraInput-Python-pypi/) |
| Python/conda-forge | custom_channel_install_verified_requires_conda_forge_review | [fyrainput](https://raw.githubusercontent.com/TitanCSA/sdk-packages/089bc73095aa8eda89bacbe10d0b9e58394b0207/conda-channel) [Source](packaging/conda/) |
| Rust/cargo | published_install_verified | [fyrainput](https://crates.io/crates/fyrainput) [Source](FyraInput-Rust-cargo/) |
| JavaScript/npm | awaiting_browser_publication_authentication | [fyrainput](https://www.npmjs.com/package/fyrainput) [Source](FyraInput-JavaScript-npm/) |
| Java/maven | published_install_verified | [fyrainput](https://central.sonatype.com/artifact/io.github.titancsa/fyrainput/1.0.0) [Source](FyraInput-Java-maven/) |
| Java/jitpack | published_install_verified | [fyrainput](https://jitpack.io/#TitanCSA/FyraInput-SDK/java-sdk-v1.0.0) [Source](FyraInput-Java-maven/) |
| Go/modules | published_install_verified | [fyrainput](https://pkg.go.dev/github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules@v1.0.0) [Source](FyraInput-Go-modules/) |
| Go/pkg-go-dev | indexed_verified | [Documentation](https://pkg.go.dev/github.com/TitanCSA/FyraInput-SDK/FyraInput-Go-modules@v1.0.0) |
| PowerShell/gallery | published_install_verified | [FyraInput](https://www.powershellgallery.com/packages/FyraInput/1.0.0) [Source](FyraInput-PowerShell-gallery/) |
| Dart/pub-dev | published_install_verified | [fyrainput](https://pub.dev/packages/fyrainput) [Source](FyraInput-Dart-pub-dev/) |
| Ruby/rubygems | published_install_verified | [fyrainput](https://rubygems.org/gems/fyrainput) [Source](FyraInput-Ruby-rubygems/) |
| PHP/packagist | composer_source_and_tag_published | [titancsa/fyrainput](https://packagist.org/packages/titancsa/fyrainput) |

Native SDK source and CMake/Conan/vcpkg/NuGet recipes share [`packaging/native`](packaging/native/LAYOUT.md). Previous release archives and tags remain unchanged.

Application and driver prerequisites and original licensing remain those documented by each SDK. No driver installer is bundled with these source packages.
