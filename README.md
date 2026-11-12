# SeuratEM

<!-- SEURATEM_LATEST_RELEASE_START -->
**[Download the latest SeuratEM release](https://github.com/MJMJ666/SeuratEM/releases/latest)**

Current release: **v1.1.7**. Updates include direct resolution sweeps, saved-resolution gene-set scoring, comparison PNG/PDF export, compressed large inputs and authenticated legacy workspace-run recovery. See the release notes and acceptance status for details.
<!-- SEURATEM_LATEST_RELEASE_END -->


SeuratEM builds on the original Seurat plug-in for SeqGeq, developed and distributed by BD/Waters.

SeuratEM is a SeqGeq plug-in for preparing, clustering, and visualizing single-cell data. Choose **RNA-only** or **protein/ADT-only** analysis, or combine RNA and ADT using **weighted nearest neighbors (WNN)**.

For paired pseudobulk differential expression between two SeqGeq populations, see the companion [DigDEGs repository](https://github.com/MJMJ666/DigDEGs).

## What you can do

- Combine compatible source files with multi-file UNION and track sample and cell identities with SampleKey and CellUID.
- Cluster cells, visualize the results, and run marker analysis or gene-set scoring.
- Test clustering resolutions, compare saved results, and reopen or import supported saved runs.
- Export an Analysis Package for downstream work.

**[Download the latest SeuratEM release](https://github.com/MJMJ666/SeuratEM/releases/latest)**

## Install

1. Install SeqGeq and R. Set the plug-ins folder and R location in SeqGeq’s Diagnostics preferences.
2. Place the SeuratEM JAR from the latest release in that folder. Keep one installed SeuratEM JAR at a time and store ZIP archives and development folders elsewhere.
3. Restart SeqGeq. Open SeuratEM and choose **Check/repair software…** to verify R and install required packages as needed.

## Start an analysis

Select a population in SeqGeq, open SeuratEM from the **Plugins** menu, and choose an analysis route. Review the settings, run the analysis, then inspect the returned populations and plots. Save the SeqGeq workspace to retain its run entry.

## Documentation and support

- `SeuratEM_Practical_User_Manual_v52.docx` walks through installation, UNION, analysis, scoring, and saved runs. Older screenshots and run records may retain earlier version labels.
- The **SeuratEM User Support Handoff** is the starting point for troubleshooting. Include the plug-in version, the window and action, any exact error message, and the saved diagnostics ZIP when available.
- The **SeuratEM Development Audit** contains implementation, build, and validation records for developers.
