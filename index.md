## Fukan System Release Notes

Fukan System version numbers are determinted by date, in Japan Standard Time
(JST), at the time the release is built for the canarying test server.

### 20181030 Major Updates (*in testing*)

- General
  - Preserve view all option between page transitions.
- Houga analysis
  - Improve analysis quality (**Incompatible change**).
  - Use a static value for the random seed.
  - Update the Japanese translation.
- Move the Changelog to
  [https://fukansystem.github.io](https://fukansystem.github.io).
- Major infrastructure updates.

### 20181003 Minor Updates

- Fix the dataset search form displaying in two lines.
- Minor infrastructure updates.

### 20181001.1 Major updates

- Improve Houga analysis and fixed some minor bugs.
- Major infrastructure improvement around task execution.
- Fix PubMed parser to check RefType for citations.
- Prevents overview analysis from running with bigger datasets.
- Fix a bug which causes a heavy delay at logging.
- Dataset upload form only accepts a zip file.
- Various infrastructure updates.

### 20180920 Minor updates

- Prevents Houga analysis from running with bigger datasets.
- Minor infrastructure updates.

### 20180911.1 Bugfix and minor updates

- Fix a bug that prevents some facet lists from loading.
- Minor infrastructure updates.

### 20180905.3 Major Updates

- Add modularity maximization by louvain method for clustering.
- Various minor bug fixes.
- Various infrastructure updates.

### 20180901 Minor Updates

- Move the task status section to the system status page.
- Some infrastructure updates.

### 20180831.2 Major Updates

- Support PubMed dataset.
- Fix a bug that the graphtool does not work well with cluster sets.
- Increase the number of elements in the summary.
- Keep the open state of summary accordions while switching clusters.
- Various code cleanup.

### 20180825 Infrastructure Updates

- Various infrastructure updates.

### 20180810.3 Major Updates

- Support more fields for sorting in Houga analyses.
- Support downloading result files of Houga analyses.
- Faster keyword extraction.
- Various infrastructure updates.
- Major code cleanup.

### 20180730.1 Infrastructure Updates

- Various infrastructure updates.

### 20180705 Hotfix

- Hotfix for a bug preventing houga analysis.

### 20180704.4 Various updates

- Improve the link detection for Scopus data.
- Support the new header of Derwent Innovation patent data.
- Various infrastructure updates.

### 20180610.1 Bugfix and various updates

- Fix a bug which does not check permission for subclustering correctly.
- Remove the legacy graph tool and heatmap.

### 20180529.2 Hotfix

- Infrastructure hotfix.

### 20180528.1 Various updates

- Remove the warning about the disruption.
- Various infrastructure updates.

### 20180525 Minor update

- Bump Django version.

### 20180521.1 Minor updates

- Fix the UI of the heatmap parameter.
- Various infrastructure updates.

### 20180518.1 Minor updates

- Improve task retrying.
- Fix the potential security vulnerability.

### 20180516.3: Major bug fixes and various updates

- Incredibly faster subclustering.
- Fix the legacy subclustering with selected clusters.
- Fix the TFIDF calculation of the legacy subclustering.
- Fix the analysis delete button.
- Fix the potential bug which may keep a task at executing state.
- Update the changelog page.

### 20180515.2: Major bug fixes

- Fix counting the number of running tasks.
- Fix counting the number of waiting tasks
- Fix the bug which prevents workers from running tasks.
- Fix the bug which prevents tasks from running.
- Add a note about the recent disruption.

### 20180511: Minor update

- Remove the total error count from the sidebar.

### 20180508: Various bug fixes

- Fix analysis download button.
- Make houga analysis view faster.
- Remove the browser version checking.
