# ReVanced Repo ![downloadCount](https://img.shields.io/github/downloads/LeddaZ/revanced-repo/total?color=blue&label=Downloads)
This repo template will allow you to build non-root ReVanced and ReVanced Music using GitHub Actions. This will help people who don't want to setup build environments on their machines.

This will build non-root ReVanced and ReVanced Music with all patches except `predictive-back-gesture` and `premium-heading`, they can be configured (or disabled) from the ReVanced settings menu in the app.

You can modify the `scripts/build.sh` script to choose the patches you want. A list of available patches and their descriptions can be found [here](https://github.com/revanced/revanced-patches).

### Latest supported versions
- YouTube: `18.03.36`
- YouTube Music: `5.39.52`

## How to setup
1. Fork or create a new repository using this repository as a template ([Guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)). DO NOT FORK if you need to set the new repo to private.
2. [Set up signing](signing.md) (if you don't want to, you can remove the signing part in the three workflows)

## How to build
1. Go to Actions -> All workflows -> Choose what you want to build ([Example](images/workflow_run.png))
2. Run the workflow
3. Download the APKs from the latest release ([Example](images/build_release.png))
