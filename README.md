<p align="center">
    <img src="/.github/home-page-images/laradock-logo.jpg?raw=true" alt="Laradock Logo"/>
</p>

<p align="center">
   <a href="http://laradock.io/contributing"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" alt="contributions welcome"></a>
   <a href="https://github.com/laradock/laradock/network"><img src="https://img.shields.io/github/forks/laradock/laradock.svg" alt="GitHub forks"></a>
   <a href="https://github.com/laradock/laradock/issues"><img src="https://img.shields.io/github/issues/laradock/laradock.svg" alt="GitHub issues"></a>
   <a href="https://github.com/laradock/laradock/stargazers"><a href="#backers" alt="sponsors on Open Collective"><img src="https://opencollective.com/laradock/backers/badge.svg" /></a> <a href="#sponsors" alt="Sponsors on Open Collective"><img src="https://opencollective.com/laradock/sponsors/badge.svg" /></a> <img src="https://img.shields.io/github/stars/laradock/laradock.svg" alt="GitHub stars"></a>
   <a href="https://github.com/laradock/laradock/actions/workflows/main-ci.yml"><img src="https://github.com/laradock/laradock/actions/workflows/main-ci.yml/badge.svg" alt="GitHub CI"></a>
   <a href="https://travis-ci.org/laradock/laradock"><img src="https://travis-ci.org/laradock/laradock.svg?branch=master" alt="Build status"></a>
   <a href="https://raw.githubusercontent.com/laradock/laradock/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="GitHub license"></a>
</p>

<p align="center"><b>Full PHP development environment based on Docker.</b></p>

<p align="center">
    <a href="http://zalt.me"><img src="http://forthebadge.com/images/badges/built-by-developers.svg" alt="forthebadge" width="180"></a>
</p>

<br>
<br>

<h4 align="center" style="color:#7d58c2">Use Docker First - Learn About It Later!</h4>

<p align="center">
	<a href="http://laradock.io">
	   <img src="https://raw.githubusercontent.com/laradock/laradock/master/.github/home-page-images/documentation-button.png" width="300px" alt="Laradock Documentation"/>
	</a>
</p>


## ENV Setting
- .env.example > .env 변경하여 사용하기

## 실행 명령어
- start : docker-compose up -d nginx mysql
  1. start 시 php-fpm 종류들 자동 실행
- stop : docker-compose stop
- build : docker-compose build nginx mysql php-fpm php-fpm7.0 php-fpm5.6
  1. 해당되는 컨테이너 build
  2. 캐시 옵션 여부 --no-cache

## nginx log
- ./logs/nginx/

## xdebug
- PHPSTORM Setting

![img.png](img.png)

![img_1.png](img_1.png)

![img_2.png](img_2.png)
