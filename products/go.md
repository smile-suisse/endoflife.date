---
title: Go
permalink: /go
alternate_urls:
-   /golang
category: lang
releasePolicyLink: https://golang.org/doc/devel/release.html#policy
changelogTemplate: https://github.com/golang/go/issues?q=milestone%3AGo__LATEST__
eolColumn: Supported
versionCommand: go version
releaseDateColumn: true
sortReleasesBy: 'cycleShortHand'
auto:
-   git: https://github.com/golang/go.git
    regex: ^go(?<major>[1-9]\d*)\.(?<minor>0|[1-9]\d*)\.?(?<patch>0|[1-9]\d*)?$
releases:
-   releaseCycle: "1.18"
    cycleShortHand: 118
    eol: false
    latest: "1.18.2"
    latestReleaseDate: 2022-05-10
    releaseDate: 2022-03-15
-   releaseCycle: "1.17"
    cycleShortHand: 117
    eol: false
    latest: "1.17.10"
    latestReleaseDate: 2022-05-10
    releaseDate: 2021-08-16
-   releaseCycle: "1.16"
    cycleShortHand: 116
    eol: true
    latest: "1.16.15"
    latestReleaseDate: 2022-03-03
    releaseDate: 2021-02-16
-   releaseCycle: "1.15"
    cycleShortHand: 115
    eol: true
    latest: "1.15.15"
    latestReleaseDate: 2021-08-04
    releaseDate: 2020-08-11
-   releaseCycle: "1.14"
    cycleShortHand: 114
    eol: true
    latest: "1.14.15"
    latestReleaseDate: 2021-02-04
    releaseDate: 2020-02-25
-   releaseCycle: "1.13"
    cycleShortHand: 113
    eol: true
    latest: "1.13.15"
    latestReleaseDate: 2020-08-06
    releaseDate: 2019-09-03
-   releaseCycle: "1.12"
    cycleShortHand: 112
    eol: true
    latest: "1.12.17"
    latestReleaseDate: 2020-02-12
    releaseDate: 2019-02-25
-   releaseCycle: "1.11"
    cycleShortHand: 111
    eol: true
    latest: "1.11.13"
    latestReleaseDate: 2019-08-13
    releaseDate: 2018-08-24
-   releaseCycle: "1.10"
    cycleShortHand: 110
    eol: true
    latest: "1.10.8"
    latestReleaseDate: 2019-01-23
    releaseDate: 2018-02-16

---

> [Go](https://golang.org/) is an open source programming language that makes it easy to build simple, reliable, and efficient software.

Each major Go release is supported until there are two newer major releases. For example, Go 1.5 was supported until the Go 1.7 release, and Go 1.6 was supported until the Go 1.8 release. It fixes critical problems, including critical security problems, in supported releases as needed by issuing minor revisions (for example, Go 1.6.1, Go 1.6.2, and so on). The security policy can be found at <https://golang.org/security>.
