# gg582 취향 맥락 지형도

3D 지구본 기반 개인 취향 맥락 지형도 포트폴리오.

- **라이브 데모**: https://gg582-profile.github.io

## 구성

| 파일 | 역할 |
|------|------|
| `index.html` | Three.js + Globe.gl 3D 지구본 시각화 |
| `macro_graph_data.json` | 국가별 활성/비활성 노드 데이터 |
| `knowledge_base/countries_kb.json` | 국가별 소비 맥락 지식 베이스 |
| `crawled_user_sites.json` | 실측 크롤링된 사용자 소유 블로그 데이터 |

## 배포

`main` 브랜치 푸시 시 GitHub Actions가 자동으로 GitHub Pages에 배포합니다.
