# Project Bird Racing Assets - Development

Development files for assets used by the `Project Bird Racing` project.

All development files for the in game assets are stored in this repository. When an asset is ready to be used, it should be copied into the `production_assets` directory.

## Production Assets

The `production_assets` directory is a git submodule, pointing to the [assets](https://github.com/snowmeltarcade/projectbirdracing-assets) repository. The assets repository is used by the [main game repository](https://github.com/snowmeltarcade/projectbirdracing) to access assets in its `data` directory.

Only assets ready to be used in game should be copied to the `production_assets` directory.

## Releases

Each game release will have a respective branch in this repository.
