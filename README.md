# inat-curated-species-list

A tool to query iNaturalist for all observations made by one or more users in a specific taxon and place, and derive a curated list of all unique species, along with the option to download it. This allows you to create tailored list of species that have been approved by a group of experts, rather than rely on the community "research grade" standard.

### Demo

You can [access the script here](https://imerss.github.io/inat-curated-species-list/), but if you're a dev, please download it and run it locally. 

<kbd>
  <img src="./resources/screenshot.png" />
</kbd>

                                             
## Run locally

The script requires npm and node. Run:

- `npm install`
- `npm run start`

## Generate 

To use this tool programmatically, do the following:

- edit the root `./constants.js` file to change the usernames, place and taxon. Get these values from iNat.
- Clone the repo,
- In the root, run: `npm install`
- Run `node generate.js`. That should generate a `./dist/data.json` file with the results of the query.
