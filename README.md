# Ellie's Desktop

AI와 프로그래밍을 공부하며 배운 내용과 일상을 기록하는 개인 블로그입니다.

[블로그 방문하기](https://e0917132.github.io)

## 기록하는 내용

- AI 학습과 실험
- Python 등 프로그래밍 학습 기록
- 일상과 생각

## 블로그 관리

| 작업 | 파일·폴더 |
| --- | --- |
| 글 작성 | [`_posts/`](_posts/)에 `YYYY-MM-DD-제목.md` 추가 |
| 블로그 이름·주소·기본 설정 | [`_config.yml`](_config.yml) |
| 자기소개 | [`_data/about_me.yml`](_data/about_me.yml) |
| 카테고리 | [`_data/categories.yml`](_data/categories.yml) |
| 프로젝트·음악 | [`_data/projects.yml`](_data/projects.yml) · [`_data/music.yml`](_data/music.yml) |
| 소개 페이지 | [`pages/about.md`](pages/about.md) |
| 기타 페이지·검색 데이터 | [`pages/`](pages/) |
| 이미지 | [`assets/images/`](assets/images/) |

### 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

실행 후 <http://localhost:4000>에서 확인합니다. `_config.yml`을 수정하면 서버를 다시 실행합니다.

## 원본 테마와 출처

이 블로그는 **wlswo가 공개한 Ephemeris 테마**를 가져와 개인 블로그로 구성했습니다.
macOS 데스크톱 형태의 디자인과 Dock, Finder, Spotlight, 창 관리 등 기본 인터페이스는 원본 테마에서 제공하는 기능입니다.
이 저장소에서는 해당 테마를 바탕으로 블로그 정보, 카테고리, 개인 글 등을 설정하고 관리합니다.

| 항목 | 출처 |
| --- | --- |
| 원본 테마 | **Ephemeris** — macOS 스타일의 Jekyll 블로그 테마 |
| 원본 저장소 | [wlswo/macos-style-blog-theme](https://github.com/wlswo/macos-style-blog-theme) |
| 테마 제작자 | [wlswo](https://github.com/wlswo) |
| 원본 데모·블로그 | [wlswo.me](https://wlswo.me) |

### 저작권과 외부 리소스

테마 코드의 저작권과 MIT 라이선스는 [LICENSE](LICENSE), 이미지·글꼴·외부 라이브러리 등의 출처와 이용 조건은 [NOTICE.md](docs/NOTICE.md)를 참고하세요.

### 테마 사용 설명서

설정과 꾸미기 등 자세한 방법은 [보관된 한국어 설명서](docs/theme/README.ko.md) 또는 [보관된 영문 설명서](docs/theme/README.md)를 참고하세요.
