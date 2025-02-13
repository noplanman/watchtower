<p align="center">
  <img src="https://0x12b.com/watchtower-logo.png" width="450" />
</p>
<h1 align="center">
  Watchtower
</h1>

<p align="center">
  A process for automating Docker container base image updates.
  <br/><br/>
  <a href="https://circleci.com/gh/containrrr/watchtower">
    <img alt="Circle CI" src="https://circleci.com/gh/containrrr/watchtower.svg?style=shield" />
  </a>
  <a href="https://godoc.org/github.com/containrrr/watchtower">
    <img alt="GoDoc" src="https://godoc.org/github.com/containrrr/watchtower?status.svg" />
  </a>
  <a href="https://microbadger.com/images/containrrr/watchtower">
    <img alt="Microbadger" src="https://images.microbadger.com/badges/image/containrrr/watchtower.svg" />
  </a>
  <a href="https://goreportcard.com/report/github.com/containrrr/watchtower">
    <img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/containrrr/watchtower" />
  </a>
  <a href="https://github.com/containrrr/watchtower/releases">
    <img alt="latest version" src="https://img.shields.io/github/tag/containrrr/watchtower.svg" />
  </a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img alt="Apache-2.0 License" src="https://img.shields.io/github/license/containrrr/watchtower.svg" />
  </a>
  <a href="https://www.codacy.com/app/simskij/watchtower">
    <img alt="Codacy Badge" src="https://api.codacy.com/project/badge/Grade/3a4d0fcfd26d45b09b1d7ea3c8c13744"/>
  </a>
  <a href="https://www.codacy.com/app/simskij/watchtower?utm_source=github.com&utm_medium=referral&utm_content=containrrr/watchtower&utm_campaign=Badge_Coverage">
    <img alt="Codacy Badge" src="https://api.codacy.com/project/badge/Coverage/3a4d0fcfd26d45b09b1d7ea3c8c13744" />
  </a>
  <a href="https://gitter.im/containrrr/watchtower?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge">
    <img alt="Join the chat at https://gitter.im/containrrr/watchtower" src="https://badges.gitter.im/containrrr/watchtower.svg" />
  </a>
  <a href="#contributors">
    <img alt="All Contributors" src="https://img.shields.io/badge/all_contributors-30-orange.svg?style=flat-square" />
  </a>
  <a href="https://hub.docker.com/r/containrrr/watchtower">
    <img alt="Pulls from DockerHub" src="https://img.shields.io/docker/pulls/containrrr/watchtower.svg?style=flat-square" />
  </a>
</p>

## Quick Start

With watchtower you can update the running version of your containerized app simply by pushing a new image to the Docker Hub or your own image registry. Watchtower will pull down your new image, gracefully shut down your existing container and restart it with the same options that were used when it was deployed initially. Run the watchtower container with the following command:

```
$ docker run -d \
    --name watchtower \
    -v /var/run/docker.sock:/var/run/docker.sock \
    containrrr/watchtower
```

## Documentation
The full documentation is available at https://containrrr.github.io/watchtower.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="http://codelica.com"><img src="https://avatars3.githubusercontent.com/u/386101?v=4" width="100px;" alt="James"/><br /><sub><b>James</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=Codelica" title="Tests">⚠️</a> <a href="#ideas-Codelica" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://kopfkrieg.org"><img src="https://avatars2.githubusercontent.com/u/5047813?v=4" width="100px;" alt="Florian"/><br /><sub><b>Florian</b></sub></a><br /><a href="#review-KopfKrieg" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/containrrr/watchtower/commits?author=KopfKrieg" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/bdehamer"><img src="https://avatars1.githubusercontent.com/u/398027?v=4" width="100px;" alt="Brian DeHamer"/><br /><sub><b>Brian DeHamer</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=bdehamer" title="Code">💻</a> <a href="#maintenance-bdehamer" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/rosscado"><img src="https://avatars1.githubusercontent.com/u/16578183?v=4" width="100px;" alt="Ross Cadogan"/><br /><sub><b>Ross Cadogan</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=rosscado" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/stffabi"><img src="https://avatars0.githubusercontent.com/u/9464631?v=4" width="100px;" alt="stffabi"/><br /><sub><b>stffabi</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=stffabi" title="Code">💻</a> <a href="#maintenance-stffabi" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/ATCUSA"><img src="https://avatars3.githubusercontent.com/u/3581228?v=4" width="100px;" alt="Austin"/><br /><sub><b>Austin</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=ATCUSA" title="Documentation">📖</a></td>
    <td align="center"><a href="https://labs.ctl.io"><img src="https://avatars2.githubusercontent.com/u/6181487?v=4" width="100px;" alt="David Gardner"/><br /><sub><b>David Gardner</b></sub></a><br /><a href="#review-davidgardner11" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/containrrr/watchtower/commits?author=davidgardner11" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/dolanor"><img src="https://avatars3.githubusercontent.com/u/928722?v=4" width="100px;" alt="Tanguy ⧓ Herrmann"/><br /><sub><b>Tanguy ⧓ Herrmann</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=dolanor" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/rdamazio"><img src="https://avatars3.githubusercontent.com/u/997641?v=4" width="100px;" alt="Rodrigo Damazio Bovendorp"/><br /><sub><b>Rodrigo Damazio Bovendorp</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=rdamazio" title="Code">💻</a> <a href="https://github.com/containrrr/watchtower/commits?author=rdamazio" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.taisun.io/"><img src="https://avatars3.githubusercontent.com/u/1852688?v=4" width="100px;" alt="Ryan Kuba"/><br /><sub><b>Ryan Kuba</b></sub></a><br /><a href="#infra-thelamer" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/cnrmck"><img src="https://avatars2.githubusercontent.com/u/22061955?v=4" width="100px;" alt="cnrmck"/><br /><sub><b>cnrmck</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=cnrmck" title="Documentation">📖</a></td>
    <td align="center"><a href="http://harrywalter.co.uk"><img src="https://avatars3.githubusercontent.com/u/338588?v=4" width="100px;" alt="Harry Walter"/><br /><sub><b>Harry Walter</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=haswalt" title="Code">💻</a></td>
    <td align="center"><a href="http://projectsperanza.com"><img src="https://avatars3.githubusercontent.com/u/74515?v=4" width="100px;" alt="Robotex"/><br /><sub><b>Robotex</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=Robotex" title="Documentation">📖</a></td>
    <td align="center"><a href="http://geraldpape.io"><img src="https://avatars0.githubusercontent.com/u/1494211?v=4" width="100px;" alt="Gerald Pape"/><br /><sub><b>Gerald Pape</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=ubergesundheit" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/fomk"><img src="https://avatars0.githubusercontent.com/u/17636183?v=4" width="100px;" alt="fomk"/><br /><sub><b>fomk</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=fomk" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/svengo"><img src="https://avatars3.githubusercontent.com/u/2502366?v=4" width="100px;" alt="Sven Gottwald"/><br /><sub><b>Sven Gottwald</b></sub></a><br /><a href="#infra-svengo" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://liberapay.com/techknowlogick/"><img src="https://avatars1.githubusercontent.com/u/164197?v=4" width="100px;" alt="techknowlogick"/><br /><sub><b>techknowlogick</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=techknowlogick" title="Code">💻</a></td>
    <td align="center"><a href="http://log.c5t.org/about/"><img src="https://avatars1.githubusercontent.com/u/1449568?v=4" width="100px;" alt="waja"/><br /><sub><b>waja</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=waja" title="Documentation">📖</a></td>
    <td align="center"><a href="http://scottalbertson.com"><img src="https://avatars2.githubusercontent.com/u/154463?v=4" width="100px;" alt="Scott Albertson"/><br /><sub><b>Scott Albertson</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=salbertson" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/huddlesj"><img src="https://avatars1.githubusercontent.com/u/11966535?v=4" width="100px;" alt="Jason Huddleston"/><br /><sub><b>Jason Huddleston</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=huddlesj" title="Documentation">📖</a></td>
    <td align="center"><a href="https://npstr.space/"><img src="https://avatars3.githubusercontent.com/u/6048348?v=4" width="100px;" alt="Napster"/><br /><sub><b>Napster</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=napstr" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/darknode"><img src="https://avatars1.githubusercontent.com/u/809429?v=4" width="100px;" alt="Maxim"/><br /><sub><b>Maxim</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=darknode" title="Code">💻</a> <a href="https://github.com/containrrr/watchtower/commits?author=darknode" title="Documentation">📖</a></td>
    <td align="center"><a href="https://schmitt.cat"><img src="https://avatars0.githubusercontent.com/u/17984549?v=4" width="100px;" alt="Max Schmitt"/><br /><sub><b>Max Schmitt</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=mxschmitt" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/cron410"><img src="https://avatars1.githubusercontent.com/u/3082899?v=4" width="100px;" alt="cron410"/><br /><sub><b>cron410</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=cron410" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/Cardoso222"><img src="https://avatars3.githubusercontent.com/u/7026517?v=4" width="100px;" alt="Paulo Henrique"/><br /><sub><b>Paulo Henrique</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=Cardoso222" title="Documentation">📖</a></td>
    <td align="center"><a href="https://coded.io"><img src="https://avatars0.githubusercontent.com/u/107097?v=4" width="100px;" alt="Kaleb Elwert"/><br /><sub><b>Kaleb Elwert</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=belak" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/wmbutler"><img src="https://avatars1.githubusercontent.com/u/1254810?v=4" width="100px;" alt="Bill Butler"/><br /><sub><b>Bill Butler</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=wmbutler" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.mariotacke.io"><img src="https://avatars2.githubusercontent.com/u/4942019?v=4" width="100px;" alt="Mario Tacke"/><br /><sub><b>Mario Tacke</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=mariotacke" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://markwoodbridge.com"><img src="https://avatars2.githubusercontent.com/u/1101318?v=4" width="100px;" alt="Mark Woodbridge"/><br /><sub><b>Mark Woodbridge</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=mrw34" title="Code">💻</a></td>
    <td align="center"><a href="http://www.arcticbit.se"><img src="https://avatars0.githubusercontent.com/u/1596025?v=4" width="100px;" alt="Simon Aronsson"/><br /><sub><b>Simon Aronsson</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=simskij" title="Code">💻</a> <a href="#maintenance-simskij" title="Maintenance">🚧</a> <a href="#review-simskij" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/Ansem93"><img src="https://avatars3.githubusercontent.com/u/6626218?v=4" width="100px;" alt="Ansem93"/><br /><sub><b>Ansem93</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=Ansem93" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/lukapeschke"><img src="https://avatars1.githubusercontent.com/u/17085536?v=4" width="100px;" alt="Luka Peschke"/><br /><sub><b>Luka Peschke</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=lukapeschke" title="Code">💻</a> <a href="https://github.com/containrrr/watchtower/commits?author=lukapeschke" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/zoispag"><img src="https://avatars0.githubusercontent.com/u/21138205?v=4" width="100px;" alt="Zois Pagoulatos"/><br /><sub><b>Zois Pagoulatos</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=zoispag" title="Code">💻</a></td>
    <td align="center"><a href="https://alexandre.menif.name"><img src="https://avatars0.githubusercontent.com/u/16152103?v=4" width="100px;" alt="Alexandre Menif"/><br /><sub><b>Alexandre Menif</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=alexandremenif" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/chugunov"><img src="https://avatars1.githubusercontent.com/u/4140479?v=4" width="100px;" alt="Andrey"/><br /><sub><b>Andrey</b></sub></a><br /><a href="https://github.com/containrrr/watchtower/commits?author=chugunov" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
