<div align="center" style="display: block; margin-left: auto; margin-right: auto;">  
    
  <img align="left" src="https://cdn.boredht.ml/images/logo.png" alt="logo" height="42" width="42">
  <img align="right" src="https://cdn.schgnd.ml/images/logo.png" alt="logo" height="42" width="42">
  <h1>Badges for Bored Enterainment</h1>
  
  [![pages-build-deployment](https://github.com/Bored-Entertainment/badges/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Bored-Entertainment/badges/actions/workflows/pages/pages-build-deployment)
  ![license](https://badgen.net/github/license/Bored-Entertainment/badges)
  ![last commit](https://img.shields.io/github/last-commit/Bored-Entertainment/badges)
  ![size](https://github-size-badge.herokuapp.com/Bored-Entertainment/badges.svg)
  [![discord](https://img.shields.io/badge/Discord-7qTNdXd?logo=discord&logoColor=white&color=5865F2)](https://discord.com/invite/7qTNdXd)
  
</div>

## Badges
- [Bored in School Right Now Badges](bored/)
- [Schoolgrounds Badges](school/)

## Domains
- [badges.boredht.ml](https://badges.boredht.ml/)
- [badges.schgnd.ml](https://badges.schgnd.ml/)

## CDNs Badges

Since [cdn.boredht.ml](https://cdn.boredht.ml/) and [cdn.schgnd.ml](https://cdn.schgnd.ml/) are the short hand of [jsDelivr](https://www.jsdelivr.com/), we have access to the [data.jsdelivr.com](https://github.com/jsdelivr/data.jsdelivr.com) for the [Bored in School Right HTML Repository](https://www.github.com/pisaucer/boredhtml) and [Schoolgrounds Repository](https://github.com/Bored-Entertainment/Schoolgrounds). So using [JamesIves/fetch-api-data-action](https://github.com/marketplace/actions/fetch-api-data) to get the data of the hits per day, week, month, and year we are able to save it to jsons. To create badges, we used [notiz-dev/github-action-json-property](https://github.com/marketplace/actions/get-json-property) to read the data from the jsons and pass the total to [emibcn/badge-action](https://github.com/marketplace/actions/badge-action). Each of the workflows are schedule to update on there own thanks to [GitHub Actions](https://github.com/features/actions). 

All of these allows us to create custom badges with precise data for our Content Delivery Network (CDN).

# Built with
- [GitHub Actions](https://github.com/features/actions)
- [jsDelivr](https://www.jsdelivr.com/)
- [data.jsdelivr.com](https://github.com/jsdelivr/data.jsdelivr.com)
- [boredhtml](https://www.github.com/pisaucer/boredhtml)
- [JamesIves/fetch-api-data-action](https://github.com/marketplace/actions/fetch-api-data)
- [notiz-dev/github-action-json-property](https://github.com/marketplace/actions/get-json-property)
- [emibcn/badge-action](https://github.com/marketplace/actions/badge-action)

# Authors

- **[PiSaucer](https://github.com/PiSaucer)** - *Initial work*

See also the list of other [contributors](https://github.com/Bored-Entertainment/cdn-badge/contributors) who participated in this project.

# Contributing

Pull requests are welcome. If you find any problem(s) in boredhtml, feel free to submit an issue. This includes stuff like vulnerabilities, or even the most trivial issues (such as typoes.) If you know how to fix an issue, feel free to make a pull request for the issue. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our [code of conduct](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us. If you would like to suggest a feature or change, submit it as an issue as well or message us on [discord](https://discord.com/invite/7qTNdXd); it will be given the appropriate tag once we have seen it. We love to discuss any major changes with you.

# License ![badge](https://badgen.net/github/license/Bored-Entertainment/badges)

Our [`LICENSE`](LICENSE) file is based off of the [MIT License](https://choosealicense.com/licenses/mit/).
