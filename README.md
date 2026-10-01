# Olakai Scoop bucket

Scoop manifests for the [Olakai](https://olakai.ai) CLI on Windows.

```powershell
scoop bucket add olakai https://github.com/olakai-ai/scoop-bucket
scoop install olakai/olakai        # stable
scoop install olakai/olakai-beta   # pre-releases
```

Both apps install the same `olakai` binary: install one.

Manifests in `bucket/` are written by the Olakai CLI release workflow. Do not edit them by hand.
Binaries are downloaded from `https://get.olakai.ai/cli/releases/`. You can also install with `npm i -g olakai-cli`.
