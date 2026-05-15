# TMU-Battlebots-Updated-Site
Updated Static Site for the TMU Battlebots Team

Site Link (to access site):  `https://TMU-BattleBots.github.io/TMU-Battlebots-Updated-Site/` 

## To Run Locally

1. Before beginning development, make sure, if 'git' cloned, to run the following command: "git submodule update --init --recursive". What this does is that it downloads the submodules that were listed under 'gitmodules' (namely, the tailbliss theme, which is what the static site runs on).
   - Side note: When cloning, the tailbliss folder doesn't get cloned, since it's source is external, not within this repo
3. Start the dev server from the project root:
	`hugo server -D`
4. Open `http://localhost:1313/` (or `http://localhost:1313/TMU-Battlebots-Updated-Site/`; whichever works best)
5. 

Note: Keep `hugo.yaml` as the active config file (done to avoid incorrect config loaded; removed `hugo.toml`)

## Additional URL Notes

- Actions uses the repo variable `SITE_URL` as baseURL

- For this repo (project site), set `SITE_URL` to `https://TMU-BattleBots.github.io/TMU-Battlebots-Updated-Site/`

If `SITE_URL` is not set, workflow gets set to default GitHub Pages URL.
