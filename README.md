# Alexander Shaw — independent consulting

Personal portfolio for CNS modelling, AI and autonomy, and scientific R&D. This repository is separate from CPNS.

## Source and deployment

The complete static source is stored in two ordinary ZIP archives to support browser uploads. Both archives are required; they contain different files, preserving the original directory structure. Videos are web-optimised.

To inspect or edit locally:

```sh
mkdir site
unzip site-part-1.zip -d site
unzip site-part-2.zip -d site
python3 -m http.server 8000 --directory site
```

The Pages workflow unpacks both archives and deploys the resulting site. For updates, rebuild both archives with each file appearing once, upload part 1 first, then part 2 with a commit message containing `Publish website`. Alternatively, run the workflow manually after both uploads. Keep each archive below 20 MB.

GitHub Pages source: GitHub Actions. A custom domain can be configured later in Settings → Pages.

Source provenance is recorded in PORTING_NOTES.md inside the archives.
