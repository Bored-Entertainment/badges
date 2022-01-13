<div align="center" style="display: block; margin-left: auto; margin-right: auto;">  
    
  <a href="https://boredht.ml/"><img align="left" src="https://cdn.boredht.ml/images/logo.png" alt="logo" height="42" width="42"></a>
  <a href="https://schgnd.ml/"><img align="right" src="https://cdn.schgnd.ml/images/logo.png" alt="logo" height="42" width="42"></a>
  <h1>Badges for Bored Enterainment</h1>
    
  <a href="https://discord.com/invite/7qTNdXd"><img src="https://img.shields.io/badge/Discord-7qTNdXd?logo=discord&logoColor=white&color=5865F2"></a>
  <a href="https://github.com/Bored-Entertainment/badges/actions/workflows/pages/pages-build-deployment"><img src="https://github.com/Bored-Entertainment/badges/actions/workflows/pages/pages-build-deployment/badge.svg"></a>
  <a href="https://github.com/Bored-Entertainment/badges/actions/workflows/badges.yml"><img src="https://github.com/Bored-Entertainment/badges/actions/workflows/badges.yml/badge.svg"></a>
  <a href="https://github.com/Bored-Entertainment/badges/commits/main"><img src="https://img.shields.io/github/last-commit/Bored-Entertainment/badges"></a>
  <a href="https://github.com/Bored-Entertainment/badges/commits/main"><img src="https://badgen.net/github/commits/Bored-Entertainment/badges/main"></a>
  <a href="LICENSE"><img src="https://badgen.net/github/license/Bored-Entertainment/badges"></a>
  <img src="https://img.shields.io/github/repo-size/Bored-Entertainment/badges?color=green">  
      
</div>

# Badges
- [Bored in School Right Now Badges](bored/)
- [Schoolgrounds Badges](school/)

# How does it work?

## CDNs Badges

Since [cdn.boredht.ml](https://cdn.boredht.ml/) and [cdn.schgnd.ml](https://cdn.schgnd.ml/) are the short hand of [jsDelivr](https://www.jsdelivr.com/), we have access to the [data.jsdelivr.com](https://github.com/jsdelivr/data.jsdelivr.com) for the [Bored in School Right HTML Repository](https://www.github.com/pisaucer/boredhtml) and [Schoolgrounds Repository](https://github.com/Bored-Entertainment/Schoolgrounds). So using [curl](https://curl.se/) to save a temporary json file we are able get the data of the hits per day, week, month, and year. To create badges, we used [notiz-dev/github-action-json-property](https://github.com/marketplace/actions/get-json-property) to read the data from the temp json and pass the total to [emibcn/badge-action](https://github.com/marketplace/actions/badge-action). We date the commits with [josStorer/get-current-time](https://github.com/marketplace/actions/get-current-time). Each of the workflows are schedule to update on there own thanks to [GitHub Actions](https://github.com/features/actions). 

All of these allows us to create custom badges with precise data for our Content Delivery Network (CDN).

## Lines of Code Badges

Since GitHub actions runs ubuntu, we are able to install [tokei](https://github.com/XAMPPRocky/tokei). After saving the data to temp json, we are able to create a badge with [emibcn/badge-action](https://github.com/marketplace/actions/badge-action). We date the commits with [josStorer/get-current-time](https://github.com/marketplace/actions/get-current-time). Loads more reliably than their [tokei.rs badge](https://tokei.rs/b1/github/PiSaucer/boredhtml).

# Built with
- [GitHub Actions](https://github.com/features/actions)
    - [notiz-dev/github-action-json-property](https://github.com/marketplace/actions/get-json-property)
    - [emibcn/badge-action](https://github.com/marketplace/actions/badge-action)
    - [actions/upload-artifact](https://github.com/marketplace/actions/upload-a-build-artifact)
    - [josStorer/get-current-time](https://github.com/marketplace/actions/get-current-time)
    - [ad-m/github-push-action](https://github.com/marketplace/actions/github-push)
- [jsDelivr](https://www.jsdelivr.com/)
    - [data.jsdelivr.com](https://github.com/jsdelivr/data.jsdelivr.com)
- [Bored Entertainment](https://github.com/Bored-Entertainment)
    - [boredhtml](https://www.github.com/pisaucer/boredhtml)
    - [schoolgrounds](https://github.com/Bored-Entertainment/schoolgrounds)

# Domains
- [badges.boredht.ml](https://badges.boredht.ml/)
- [badges.schgnd.ml](https://badges.schgnd.ml/)

# Authors

- **[PiSaucer](https://github.com/PiSaucer)** - *Initial work*

See also the list of other [contributors](https://github.com/Bored-Entertainment/cdn-badge/contributors) who participated in this project.

# Contributing

Pull requests are welcome. If you find any problem(s) in boredhtml, feel free to submit an issue. This includes stuff like vulnerabilities, or even the most trivial issues (such as typoes.) If you know how to fix an issue, feel free to make a pull request for the issue. Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our [code of conduct](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us. If you would like to suggest a feature or change, submit it as an issue as well or message us on [discord](https://discord.com/invite/7qTNdXd); it will be given the appropriate tag once we have seen it. We love to discuss any major changes with you.

# License ![badge](https://badgen.net/github/license/Bored-Entertainment/badges)

Our [`LICENSE`](LICENSE) file is based off of the [MIT License](https://choosealicense.com/licenses/mit/).

