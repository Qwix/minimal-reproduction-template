# https://github.com/renovatebot/renovate/discussions/35128

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate is matching docker images with major versions different than the current major version.

## Expected behavior

I would like to find a way for renovate to only match docker images where the major version is the same as the current version.
I need to use regex versioning for this.  I think it should be doable using matchCurrentVersion.  

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/35128
