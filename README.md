# Scott Friedman's Scoop Bucket

Scoop manifests for tools by [Scott Friedman](https://github.com/scttfrdmn).

## Installation

```powershell
scoop bucket add scttfrdmn https://github.com/scttfrdmn/scoop-bucket
scoop install <app>
```

## Available manifests

| App | Description |
|-----|-------------|
| `prism` | Project scaffolding and template management |
| `cargoship` | Enterprise data archiving for AWS |
| `cicada` | CI/CD utility |
| `aws-jupyter` | Launch Jupyter on AWS |
| `aws-rstudio` | Launch RStudio on AWS |
| `aws-vscode` | Launch VS Code on AWS |
| `lens-jupyter` | Lens Jupyter integration |
| `lens-rstudio` | Lens RStudio integration |
| `lens-vscode` | Lens VS Code integration |

## Automated updates

Manifests are updated via GoReleaser when each project publishes a release.
