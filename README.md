# ImHex SDK Action

This is the official GitHub Action to setup the ImHex SDK for building ImHex Plugins.

## Usage

To use the action, simply add the following code to your CI script.
```yaml
- name: Install SDK
  id: install_sdk
  uses: WerWolv/imhex-download-sdk@vX.Y.Z
```

Important to note, the `@vX.Y.Z` refers to the ImHex version whose SDK should be used. For example, if you want to build a plugin for ImHex version 1.32.2, use `WerWolv/imhex-download-sdk@v1.32.2`

Visit the ImHex-Plugin-Template repository if you'd like to get started
