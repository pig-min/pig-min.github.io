---
layout: page
title: About
permalink: /about/
---


# Pig-Min
Pig-Min은 인디게임에 대해 다뤘던 웹진/블로그 입니다. 원래 사이트의 소개는 [Post Indie Gaming에 대해 (About Us)](/tt/13)를 참조하세요.

# 이 사이트는?

안녕하세요. 인디 게임 웹진 Pig-Min의 기술지원을 맡고 있었던 나유령이라고 합니다.

Pig-Min은 2015년 정도까지 운영되었던 Textcube 기반 블로그 입니다. 2015년 이후에는 거의 방치되다 싶이 하다 불의의 사고로 사용중이던 웹호스팅을 날려먹었고, 사이트는 완전 폐쇄 상태가 되었습니다.

사이트는 Textcube 기반으로 되어 있으며 Textcube에는 블로그 데이터(포스트, 첨부파일 등)를 하나의 XML 파일로 내보내기/가져오기를 하는 기능이 있었습니다.
우연히 이 기능을 활용해 만든 백업 데이터가 발견되었는데, 어떻게 다시 사이트를 살릴까에 대해서는 고민이 되었습니다.

* 지금 다시 Textcube 블로그를 돌리기에는 보안적인 면이 걱정됨
* 이전에는 Textcube에서 Tistory로 이전도 가능했으나 현재는 기능이 사라짐
* 사이트 운영 비용을 최대한 절약하고 싶음
* 아카이브 용도의 사이트이기 때문에 이것저것 타협 가능
  * 포스트 작성 편의성 희생
    (제가 기술지원을 하긴 하지만, 사이트의 주 운영자는 기술자가 아닙니다)
  * 댓글/트랙백 기능이 없어도 됨

이런 점을 종합하여 Textcube 백업 데이터를 Jekyll 포스트로 변환해주는 툴인 [textcube_to_jekyll](http://github.com/iAmGhost/textcube_to_jekyll)을 만들어 [GitHub Pages](https://pages.github.com)를 통해 호스팅 하게 되었습니다.

5218개의 글을 XML 파일로부터 복원하였고, 백업 이후 작성된 글 중 일부(118개)는 archive.org 백업된 HTML을 받아 파싱하여 복원하였습니다.

[[archive.org 에서 원래 Pig-Min 사이트가 어떻게 생겼었나 보러 가기]](https://web.archive.org/web/20210119/http://www.pig-min.com/tt/)
