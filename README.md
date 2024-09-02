# Duanyll's Scoop Bucket

[![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer. This bucket contains manifests for my personal projects and other software that I use.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add duanyll https://github.com/duanyll/scoop-bucket
scoop install duanyll/<app>
```