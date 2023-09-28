<!-- markdownlint-disable-next-line first-line-h1 -->
[![OpenSSFScorecard](https://api.securityscorecards.dev/projects/github.com/nginxinc/nginx-prometheus-exporter/badge)](https://api.securityscorecards.dev/projects/github.com/nginxinc/nginx-prometheus-exporter)
[![CI](https://github.com/nginxinc/nginx-prometheus-exporter/workflows/Continuous%20Integration/badge.svg)](https://github.com/nginxinc/nginx-prometheus-exporter/actions?query=workflow%3A%22Continuous+Integration%22)
[![FOSSA Status](https://app.fossa.com/api/projects/custom%2B5618%2Fgithub.com%2Fnginxinc%2Fnginx-prometheus-exporter.svg?type=shield)](https://app.fossa.com/projects/custom%2B5618%2Fgithub.com%2Fnginxinc%2Fnginx-prometheus-exporter?ref=badge_shield)
[![Go Report Card](https://goreportcard.com/badge/github.com/nginxinc/nginx-prometheus-exporter)](https://goreportcard.com/report/github.com/nginxinc/nginx-prometheus-exporter)
![GitHub all releases](https://img.shields.io/github/downloads/nginxinc/nginx-prometheus-exporter/total?logo=github)
![GitHub release (latest by SemVer)](https://img.shields.io/github/downloads/nginxinc/nginx-prometheus-exporter/latest/total?sort=semver&logo=github)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nginxinc/nginx-prometheus-exporter?logo=github&sort=semver)](https://github.com/nginxinc/nginx-prometheus-exporter/releases/latest)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/nginxinc/nginx-prometheus-exporter?logo=go)
[![Docker Pulls](https://img.shields.io/docker/pulls/nginx/nginx-prometheus-exporter?logo=docker&logoColor=white)](https://hub.docker.com/r/nginx/nginx-prometheus-exporter)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/nginx/nginx-prometheus-exporter?logo=docker&logoColor=white&sort=semver)
[![Slack](https://img.shields.io/badge/slack-%23nginx--prometheus--exporter-green?logo=slack)](https://nginxcommunity.slack.com/channels/nginx-prometheus-exporter)

# NGINX Prometheus Exporter
fork `https://github.com/nginxinc/nginx-prometheus-exporter`

支持tengine v2.1.2，新增`nginx_http_response_time_millisecond_total`指标，用法跟原先的一样。