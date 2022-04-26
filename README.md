# Py-FEAT Archive

**This is an archival repository for py-feat prior to merging of the `docs-fixes` branch against `master` on the [original repo](https://github.com/cosanlab/py-feat)**

No development work occurs in this repo and it exists only for archival purposes of historical commits. The reason for this is that the original repo has been heavily rebased and cleaned to remove accidentally committed large files and to overhaul the organization of the code base and documentation site to make it easier for future contribution and maintenance.


This repo was created using the following steps:
1. Clone the original repo: `git clone https://github.com/cosanlab/py-feat py-feat-archive`
2. Pull all remote branches: `for b in `git branch -r | grep -v -- '->'`; do git branch --track ${b##origin/} $b; done`
3. Setting this remote as the new URL: `git remote set-url origin https://github.com/cosanlab/py-feat-archive.git` 
4. Pushing all local branches: `git push --all && git push --tags`
