<h1 align="center">
  Kirk Ward Robinson *dot* com
</h1>
<h2 align="center">
  Author Page & Blog
</h2>
<p align="center">
  kirkwardrobinson.com is an author page and blog for prolific author: Kirk Ward Robinson. 
  Built with [Hugo](https://github.com/gohugoio/hugo) site-generator and is a fork of the template/theme [Corporio](https://github.com/AminZibayi/Corporio).
</p>

<p align="center">
  <a href="https://github.com/AminZibayi/Corporio/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/AminZibayi/Corporio?style=flat-square" alt="GitHub">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/releases">
    <img src="https://img.shields.io/github/v/release/AminZibayi/Corporio?include_prereleases&style=flat-square"alt="GitHub release (latest SemVer including pre-releases)">
  </a>
  <a href="https://www.npmjs.com/package/@hyas/core">
    <img src="https://img.shields.io/npm/v/@hyas/core?style=flat-square" alt="npm (scoped)">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/actions?query=workflow%3A%22Hyas+CI%22">
    <img src="https://img.shields.io/github/workflow/status/AminZibayi/Corporio/Hyas%20CI/master?style=flat-square" alt="GitHub Workflow Status (branch)">
  </a>
  <a href="https://app.netlify.com/sites/hyas/deploys">
    <img src="https://img.shields.io/netlify/895a161c-86be-48a2-8c57-a8c5d68cd1a4?style=flat-square" alt="Netlify">
  </a>
</p>

![kirkwardrobinson.com](https://github.com/lowcache/krob/blob/master/assets/images/farmlogo.png)
<h6 align="right">
KirkWardRobinson.com logo © J.Redd R. 2024
</h6>

<h3 align="center"> 
  This project was 
</h3>

<h4 align="center">
  cloned, re-conceptualized, re-colored, rearranged, refined, edited, updated, coded, and its squsre peg was forced through the round hole to fit the very specific use-case displayed here by [J.Redd](@lowCache)
  If you prefer, or find yourself sympatico, with this version of the theme, feel free to use it in its current form, I just ask that you give the original dev credit, as he did all the heavy lifting and I just came in with as woodchipper and clumsily hacked away at it until I was able to force it to fit (square peg) my very specific and unpopular (unpopular due to a lack of interest not due to scandal, or disaster) needs.
   
</h4>

- [Demo](#demo)
- [Website Features](#website-features)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Communities](#communities)
- [License](#license)

## Demo

- [Template Demo](https://corporio.onrender.com/)
- Demo Site COMING SOON!

## Website Features

Eight features of kirkwardrobinson.com

1. **Security aware**. Will have A+ scores on [Mozilla Observatory](https://observatory.mozilla.org/analyze/corporio.onrender.com) out of the box. Easily change the default Security Headers to suit your needs.
2. **Fast by default**. Leverages the fastest static site generator, delivering optimized and minified static assets on the fastest CDNs on Render and Netlify.
3. **SEO-ready**. Uses sensible defaults for structured data, open graph, and Twitter cards. Or easily change the SEO settings to your liking.
4. **Tina Integrated**.A feature-rich headless CMS.
5. **Development tools**. Custom Development tools
6. **Responsive**.  Robust, flexible, and intuitive website that is responsibe to any device.
7. **Integrated Blog**. Modern and well-designed author landing page, as well as built-in and full-featured blog ready for publishing.
8. **Individual Titles Page(s) & Spotlight featured/newly released title(s)**. Ability to introduce books, spotlight featured titles, reader testimonials/reviews, showcase all content easily with a modern & sleek user interface
9. **Deploy-ready**. Deploy to Netlify or Render with sensible defaults. Easily use Netlify Functions, Render Redirects, and Headers.

## Documentation

_TODO_

## Contributing

You can contribute to the Corporio Hugo Theme by following the specific instructions found on the themes git repo by the author [Amin Zibayi](https://GitHub.com/AminZibayi/Corporio).

Contributions to _this_ specific repo is not needed or wanted. However, a more generic and easier to modify version of Corporio has been created and is under active development [here](https://GitHub.com/lowcache/Hugo-Corporio). Feel free to clone and alter the theme with your specific changes and issue a pull request if you feel as though your changes would serve the theme in that current iteration. 


## License

[The MIT License](https://github.com/AminZibayi/Corporio/blob/master/LICENSE)

## If you clone this repo and want to view the site through the builtin Hugo/NodeJS HTTP Server you can follow the following steps:
### Install Dependencies through your preferred package manager first:
#### Arch
```bash
sudo pacman -Sy git npm pnpm
git clone https://github.com/drpdead/krob.git /srv/http/krob && sudo chown -R $USER:$USER /srv && cd /srv/http/krob
pnpm install # if any error occur install the necessary dependencies or follow instructions to enable error free installation
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website
```
#### Ubuntu
```bash
sudo apt update && sudo apt upgrade
sudo apt install -y git npm pnpm
git clone https://github.com/drpdead/krob.git /srv/http/krob && sudo chown -R $USER:$USER /srv && cd /srv/http/krob
pnpm install # if any error occur install the necessary dependencies or follow instructions to enable error free installation
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website
```
#### Windows
run cmd.exe or windows terminal with Admin priviledges
```pwsh
winget install -e github.github- #or winget install -e --id GitHub.cli # First one has a gui
winget install -e --id pnpm.pnpm
gh clone https://github.com/drpdead/krob C:\Users\$USER\srv\krob\
cd C:\Users\$USER\srv\krob\
pnpm install
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website


