# A binder Image for visualization and visual analytics

- [Tip: speed up Binder launches by pulling github content in a Binder link with nbgitpuller](https://discourse.jupyter.org/t/tip-speed-up-binder-launches-by-pulling-github-content-in-a-binder-link-with-nbgitpuller/922) by choldgraf

- [Binder path](https://mybinder.org/v2/gh/wakita/binder-vis/master?urlpath=git-pull?repo=https://github.com/wakita/psycostat.git)

- [mybinder](https://mybinder.org) を開き、以下を設定
- GitHub = `wakita/binder-vis`
- URL to open = `https://github.com/wakita/psycostat.git`

https://mybinder.org/v2/gh/choldgraf/binder-sandbox/master?urlpath=git-pull?repo=https:%2F%2Fgithub.com%2Fdata-8%2Fmaterials-fa17

https://mybinder.org/v2/gh/wakita/binder-vis/main?urlpath=git-pull?repo=https:%2F%2Fgithub.com%2Fwakita%2Fpsycostat.git

こちらの設定は Conda に依存している。普段の環境と異なる上、イメージの作成が重い気がする。



---
# [nbgitpuller link generator](https://jupyterhub.github.io/nbgitpuller/link?tab=binder) の設定例

- BinderHub URL: `https://mybinder.org`
- Git Environment: `https://github.com/wakita/binder-vis`, branch: `main`
- Git Content Repository URL: https://github.com/wakita/psycostat, branch: `main`
- File to open: `Readme.md`
- Application to Open: `Jupyter Lab`
