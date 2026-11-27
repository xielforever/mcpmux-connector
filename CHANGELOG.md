# Changelog

## [0.4.0](https://github.com/xielforever/mcpmux-connector/compare/v0.3.0...v0.4.0) (2026-11-27)


### Features

* add autostart and system tray functionality ([#38](https://github.com/xielforever/mcpmux-connector/issues/38)) ([cc99fcf](https://github.com/xielforever/mcpmux-connector/commit/cc99fcf412f24f48edba12b8f0359fa71b5247c6))
* Add custom server configuration fields (env vars, args, headers) ([#54](https://github.com/xielforever/mcpmux-connector/issues/54)) ([37ce0f5](https://github.com/xielforever/mcpmux-connector/commit/37ce0f575883680e2ee12354e3bfea48e7a9337e))
* add Homebrew tap support and ad-hoc macOS signing ([#79](https://github.com/xielforever/mcpmux-connector/issues/79)) ([b07f1a3](https://github.com/xielforever/mcpmux-connector/commit/b07f1a3a6a11fd1ae944368fa0909838ffb41292))
* add Linux APT repository and install infrastructure ([#85](https://github.com/xielforever/mcpmux-connector/issues/85)) ([473eb1a](https://github.com/xielforever/mcpmux-connector/commit/473eb1aeb25c8e01d2111b9e1a82e8fee1a4d4dd))
* add select, file_path, and directory_path input types ([#121](https://github.com/xielforever/mcpmux-connector/issues/121)) ([942ee1a](https://github.com/xielforever/mcpmux-connector/commit/942ee1ae88f60aa1454bc97cec3839bcacf74454))
* apply McpMux branding to OAuth authorization pages ([#74](https://github.com/xielforever/mcpmux-connector/issues/74)) ([c84e036](https://github.com/xielforever/mcpmux-connector/commit/c84e036b13b276520b8433439954303dbe3dbaed))
* Capture and stream process stderr to server log manager ([#63](https://github.com/xielforever/mcpmux-connector/issues/63)) ([96795b0](https://github.com/xielforever/mcpmux-connector/commit/96795b0b54ecfaa9743bb9e6045bfc86ddadcc2f))
* capture MCP protocol logging notifications in server connection logs ([#76](https://github.com/xielforever/mcpmux-connector/issues/76)) ([0587741](https://github.com/xielforever/mcpmux-connector/commit/058774135fed2c0220a4900372f665e88eb3dff5))
* file-based keychain fallback for headless Linux/WSL ([#103](https://github.com/xielforever/mcpmux-connector/issues/103)) ([9b60e0b](https://github.com/xielforever/mcpmux-connector/commit/9b60e0bbe47a2318e7352efd3ba8b1888f393f38))
* implement Tauri updater functionality ([#36](https://github.com/xielforever/mcpmux-connector/issues/36)) ([d355c68](https://github.com/xielforever/mcpmux-connector/commit/d355c68a4b33901adb7f9be8c0765252f8c3577f))
* initial release of McpMux desktop app ([72181e2](https://github.com/xielforever/mcpmux-connector/commit/72181e2b462f4f70eb586758e8bd029dcb3b7631))
* post-action UX guidance, ConfirmDialog, and client auto-select ([#136](https://github.com/xielforever/mcpmux-connector/issues/136)) ([44d934c](https://github.com/xielforever/mcpmux-connector/commit/44d934c678c4d7a2eebc996928e2fb37c07d7a8e))
* redesign README, screenshots, and E2E capture ([#87](https://github.com/xielforever/mcpmux-connector/issues/87)) ([84f15cb](https://github.com/xielforever/mcpmux-connector/commit/84f15cb8b805912ca810ad00bff9f819802f4d78))
* Streamable HTTP transport with SSE notifications and E2E tests ([#61](https://github.com/xielforever/mcpmux-connector/issues/61)) ([ca5b0ff](https://github.com/xielforever/mcpmux-connector/commit/ca5b0ffab19aa395a75c5f10a18ab0e6efb1752a))
* support default values for input definitions ([#70](https://github.com/xielforever/mcpmux-connector/issues/70)) ([a1d9599](https://github.com/xielforever/mcpmux-connector/commit/a1d9599601c212c1b7054fc4c5c76f065e0ea920))
* update logo with bolder strokes and regenerate icons/screenshots ([#71](https://github.com/xielforever/mcpmux-connector/issues/71)) ([68c292c](https://github.com/xielforever/mcpmux-connector/commit/68c292c424671edf4a914484a7af570770fac71e))


### Bug Fixes

* add one-click IDE install for VS Code and Cursor ([#119](https://github.com/xielforever/mcpmux-connector/issues/119)) ([5b280fb](https://github.com/xielforever/mcpmux-connector/commit/5b280fbfdcd04165827b7662ba6896cea96deb83))
* add projectPath to tauri-action for monorepo support ([0299a23](https://github.com/xielforever/mcpmux-connector/commit/0299a23c5f995b4bae670ef709134967a19c6ee3))
* allow process restart after update and detect Homebrew version mismatch ([#134](https://github.com/xielforever/mcpmux-connector/issues/134)) ([ecdbaca](https://github.com/xielforever/mcpmux-connector/commit/ecdbacafaff573f497ce6db8614fa39993a28a32))
* Claude client icon resolving ([#68](https://github.com/xielforever/mcpmux-connector/issues/68)) ([c54128e](https://github.com/xielforever/mcpmux-connector/commit/c54128e0fbff96bd110de4e4dea45580dfad224c))
* debounce analytics search tracking to capture final query ([#132](https://github.com/xielforever/mcpmux-connector/issues/132)) ([0f17ddb](https://github.com/xielforever/mcpmux-connector/commit/0f17ddb768b5d309a3a73cc6df492f656e205f69))
* detect OAuth requirement from unexpected content-type responses ([#128](https://github.com/xielforever/mcpmux-connector/issues/128)) ([d894d17](https://github.com/xielforever/mcpmux-connector/commit/d894d17c7c4c5841b7eb39dc1d7068dbcb447656))
* don't pass APPLE_CERTIFICATE to tauri-action ([1943134](https://github.com/xielforever/mcpmux-connector/commit/19431347c63eba3ed00b408d3e6c044bd3ac8a9c))
* e2e flaky fix ([#75](https://github.com/xielforever/mcpmux-connector/issues/75)) ([d8e28f8](https://github.com/xielforever/mcpmux-connector/commit/d8e28f8fd7a6ab50d3a12d766b970d482ae2fbe2))
* enable createUpdaterArtifacts for updater signatures ([c620e56](https://github.com/xielforever/mcpmux-connector/commit/c620e56f9cae7cea4b7682ff49be37da3d1f670e))
* Fix refresh token issue ([#69](https://github.com/xielforever/mcpmux-connector/issues/69)) ([0eba047](https://github.com/xielforever/mcpmux-connector/commit/0eba047922d3313121b5dd89e62f8b6aae9fe1db))
* gracefully handle invalid Apple certificate in release builds ([bb4221f](https://github.com/xielforever/mcpmux-connector/commit/bb4221f9e4a47ff7fad041b13e432a2ed55e1f96))
* **oauth:** remove credential caching to enable automatic token refresh ([#33](https://github.com/xielforever/mcpmux-connector/issues/33)) ([f398cfa](https://github.com/xielforever/mcpmux-connector/commit/f398cfad7f1f92956f528b5e4640049de77b5ac3))
* regenerate ICO with proper sizes & increase connection timeout ([#123](https://github.com/xielforever/mcpmux-connector/issues/123)) ([2d88b25](https://github.com/xielforever/mcpmux-connector/commit/2d88b259e9ca1bbc1ac57405854d732d8437cce3))
* remove notarization env vars from tauri-action ([31ed4ed](https://github.com/xielforever/mcpmux-connector/commit/31ed4ed7a1aa8b14bb6f403939fa62652a1579d3))
* render server icon URLs as images instead of raw text ([#57](https://github.com/xielforever/mcpmux-connector/issues/57)) ([5a94708](https://github.com/xielforever/mcpmux-connector/commit/5a94708dcddd47c26183bd18c6abd348c91f976c))
* replace deprecated macos-13 runner with macos-latest ([92ad770](https://github.com/xielforever/mcpmux-connector/commit/92ad7702d2cada69df46c3a221bc2101caf17a20))
* resolve npx/node PATH on macOS GUI apps ([#113](https://github.com/xielforever/mcpmux-connector/issues/113)) ([98c013d](https://github.com/xielforever/mcpmux-connector/commit/98c013d4e6955e678949df6068c038e1b8cf00fc))
* skip Apple certificate in tauri-action when import fails ([968d4b9](https://github.com/xielforever/mcpmux-connector/commit/968d4b90b09bffc9a2432a32f2318ffde3facb88))
* stdio enable error UI state ([#104](https://github.com/xielforever/mcpmux-connector/issues/104)) ([b4598e6](https://github.com/xielforever/mcpmux-connector/commit/b4598e60e12d3389717fc2252bac8eb29e96f9c9))
* suppress console window for stdio MCP servers on Windows ([#59](https://github.com/xielforever/mcpmux-connector/issues/59)) ([98f862c](https://github.com/xielforever/mcpmux-connector/commit/98f862cae83f24c4397fe8e6204215c68b0baf92))
* taskbar icon visibility ([#83](https://github.com/xielforever/mcpmux-connector/issues/83)) ([400c4bc](https://github.com/xielforever/mcpmux-connector/commit/400c4bcce315bc7354dacb40b1cfa95a51e0edd3))
* Update screenshots and Logo ([#56](https://github.com/xielforever/mcpmux-connector/issues/56)) ([e6fb736](https://github.com/xielforever/mcpmux-connector/commit/e6fb736ca7a79c13f227cdb470e735df447ea7cd))
* ux improvements and fixes ([#42](https://github.com/xielforever/mcpmux-connector/issues/42)) ([fa52576](https://github.com/xielforever/mcpmux-connector/commit/fa52576fc79102af992f71ef059f8f7eb937a23d))
* version display & update check ([#117](https://github.com/xielforever/mcpmux-connector/issues/117)) ([b40c59b](https://github.com/xielforever/mcpmux-connector/commit/b40c59bfb7b9ec19be8848abe04e38ba6fed1422))
* wire up HTTP definition headers orthogonally from auth ([#125](https://github.com/xielforever/mcpmux-connector/issues/125)) ([04380e0](https://github.com/xielforever/mcpmux-connector/commit/04380e0979ab428351185d381001d209e6a4993b))


### Refactoring

* remove Password and Textarea from InputType enum ([#122](https://github.com/xielforever/mcpmux-connector/issues/122)) ([bd06386](https://github.com/xielforever/mcpmux-connector/commit/bd06386e04020da381135761a631ab38543ae414))


### Documentation

* add comprehensive light-theme screenshots for all features ([#47](https://github.com/xielforever/mcpmux-connector/issues/47)) ([cefa644](https://github.com/xielforever/mcpmux-connector/commit/cefa644daad6c23640db6bc767eb1dd0e43199f0))
* add mcpmux.com links and download references to README ([#64](https://github.com/xielforever/mcpmux-connector/issues/64)) ([04ab100](https://github.com/xielforever/mcpmux-connector/commit/04ab1006d68860ff6f347ef6cd68dd3d678c3352))
* add user guide with screenshots ([#130](https://github.com/xielforever/mcpmux-connector/issues/130)) ([a97a133](https://github.com/xielforever/mcpmux-connector/commit/a97a1333520fc1ac54f061344970cf493807ca87))
* add user guide with screenshots ([#131](https://github.com/xielforever/mcpmux-connector/issues/131)) ([ee28e8b](https://github.com/xielforever/mcpmux-connector/commit/ee28e8be432d2b1532f3f98067ba9004c4a18374))
* comprehensive README rewrite with features, security, and archi… ([#44](https://github.com/xielforever/mcpmux-connector/issues/44)) ([243d3a3](https://github.com/xielforever/mcpmux-connector/commit/243d3a369f34cfb02c5e82085e90c68e5bed963d))
* improve README first impression with problem/fix diagrams ([#109](https://github.com/xielforever/mcpmux-connector/issues/109)) ([b15482b](https://github.com/xielforever/mcpmux-connector/commit/b15482b32a016e3ca92753f26212f5827f744903))

## [0.3.0](https://github.com/mcpmux/mcp-mux/compare/v0.2.3...v0.3.0) (2026-02-25)


### Features

* post-action UX guidance, ConfirmDialog, and client auto-select ([#136](https://github.com/mcpmux/mcp-mux/issues/136)) ([44d934c](https://github.com/mcpmux/mcp-mux/commit/44d934c678c4d7a2eebc996928e2fb37c07d7a8e))

## [0.2.3](https://github.com/mcpmux/mcp-mux/compare/v0.2.2...v0.2.3) (2026-02-21)


### Bug Fixes

* allow process restart after update and detect Homebrew version mismatch ([#134](https://github.com/mcpmux/mcp-mux/issues/134)) ([ecdbaca](https://github.com/mcpmux/mcp-mux/commit/ecdbacafaff573f497ce6db8614fa39993a28a32))
* debounce analytics search tracking to capture final query ([#132](https://github.com/mcpmux/mcp-mux/issues/132)) ([0f17ddb](https://github.com/mcpmux/mcp-mux/commit/0f17ddb768b5d309a3a73cc6df492f656e205f69))

## [0.2.2](https://github.com/mcpmux/mcp-mux/compare/v0.2.1...v0.2.2) (2026-02-20)


### Bug Fixes

* detect OAuth requirement from unexpected content-type responses ([#128](https://github.com/mcpmux/mcp-mux/issues/128)) ([d894d17](https://github.com/mcpmux/mcp-mux/commit/d894d17c7c4c5841b7eb39dc1d7068dbcb447656))
* wire up HTTP definition headers orthogonally from auth ([#125](https://github.com/mcpmux/mcp-mux/issues/125)) ([04380e0](https://github.com/mcpmux/mcp-mux/commit/04380e0979ab428351185d381001d209e6a4993b))


### Documentation

* add user guide with screenshots ([#130](https://github.com/mcpmux/mcp-mux/issues/130)) ([a97a133](https://github.com/mcpmux/mcp-mux/commit/a97a1333520fc1ac54f061344970cf493807ca87))
* add user guide with screenshots ([#131](https://github.com/mcpmux/mcp-mux/issues/131)) ([ee28e8b](https://github.com/mcpmux/mcp-mux/commit/ee28e8be432d2b1532f3f98067ba9004c4a18374))

## [0.2.1](https://github.com/mcpmux/mcp-mux/compare/v0.2.0...v0.2.1) (2026-02-19)


### Bug Fixes

* regenerate ICO with proper sizes & increase connection timeout ([#123](https://github.com/mcpmux/mcp-mux/issues/123)) ([2d88b25](https://github.com/mcpmux/mcp-mux/commit/2d88b259e9ca1bbc1ac57405854d732d8437cce3))


### Refactoring

* remove Password and Textarea from InputType enum ([#122](https://github.com/mcpmux/mcp-mux/issues/122)) ([bd06386](https://github.com/mcpmux/mcp-mux/commit/bd06386e04020da381135761a631ab38543ae414))

## [0.2.0](https://github.com/mcpmux/mcp-mux/compare/v0.1.2...v0.2.0) (2026-02-18)


### Features

* add select, file_path, and directory_path input types ([#121](https://github.com/mcpmux/mcp-mux/issues/121)) ([942ee1a](https://github.com/mcpmux/mcp-mux/commit/942ee1ae88f60aa1454bc97cec3839bcacf74454))


### Bug Fixes

* add one-click IDE install for VS Code and Cursor ([#119](https://github.com/mcpmux/mcp-mux/issues/119)) ([5b280fb](https://github.com/mcpmux/mcp-mux/commit/5b280fbfdcd04165827b7662ba6896cea96deb83))
* version display & update check ([#117](https://github.com/mcpmux/mcp-mux/issues/117)) ([b40c59b](https://github.com/mcpmux/mcp-mux/commit/b40c59bfb7b9ec19be8848abe04e38ba6fed1422))

## [0.1.2](https://github.com/mcpmux/mcp-mux/compare/v0.1.1...v0.1.2) (2026-02-18)


### Bug Fixes

* resolve npx/node PATH on macOS GUI apps ([#113](https://github.com/mcpmux/mcp-mux/issues/113)) ([98c013d](https://github.com/mcpmux/mcp-mux/commit/98c013d4e6955e678949df6068c038e1b8cf00fc))


### Documentation

* improve README first impression with problem/fix diagrams ([#109](https://github.com/mcpmux/mcp-mux/issues/109)) ([b15482b](https://github.com/mcpmux/mcp-mux/commit/b15482b32a016e3ca92753f26212f5827f744903))

## [0.1.1](https://github.com/mcpmux/mcp-mux/compare/v0.1.0...v0.1.1) (2026-02-16)


### Bug Fixes

* file-based keychain fallback for headless Linux/WSL ([#103](https://github.com/mcpmux/mcp-mux/issues/103)) ([9b60e0b](https://github.com/mcpmux/mcp-mux/commit/9b60e0bbe47a2318e7352efd3ba8b1888f393f38))
* stdio enable error UI state ([#104](https://github.com/mcpmux/mcp-mux/issues/104)) ([b4598e6](https://github.com/mcpmux/mcp-mux/commit/b4598e60e12d3389717fc2252bac8eb29e96f9c9))

## [0.1.0](https://github.com/mcpmux/mcp-mux/compare/v0.0.1...v0.1.0) (2026-02-16)

First public release of McpMux — the unified MCP gateway and manager for AI clients.

### Features

* Unified MCP gateway — configure servers once, connect every AI client through a single endpoint
* Encrypted credential storage via OS keychain (DPAPI, Keychain, Secret Service) with AES-256-GCM field-level encryption
* Spaces for organizing servers into workspaces with per-client access key authentication
* FeatureSet filtering — fine-grained control over tools, resources, and prompts per client
* OAuth 2.1 + PKCE with automatic token refresh for OAuth-enabled MCP servers
* Server discovery — browse and install from the community registry at mcpmux.com
* Streamable HTTP transport with SSE notifications
* Stdio transport with platform-specific process isolation
* Server connection logging with MCP protocol notifications and stderr capture
* Custom server configuration fields — environment variables, arguments, and headers
* Default values for server input definitions
* McpMux-branded OAuth authorization pages
* System tray with autostart on login
* Built-in auto-updater with signed releases
* Cross-platform installers — Windows (NSIS), macOS (DMG via Homebrew), Linux (APT + AppImage + .deb)
