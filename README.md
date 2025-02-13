# spotify_EDA

# 프로젝트 소개

이 프로젝트는 [Kaggle의 Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023) 데이터 셋을 통한 EDA를 진행한 결과를 공유합니다.

음악은 과거에서부터 지속되어 현대까지 이어진 전세계 공통 문화로 자리 잡았습니다. 일상 어디에서든 쉽게 접할 수 있는 음악은 디지털 시대에 접어들면서 더욱 접근이 용이해졌고, 
이에 따라 음악의 수요와 소비가 올라갔습니다. 그중에서 해외에서 가장 큰 스트리밍 사이트인 Spotify에서 여러 해에 걸쳐 수집된 음악의 요소 데이터를 선정하였습니다. 

본 프로젝트로 얻을 수 있는 긍적적인 효과는 다음과 같습니다.

  **1. 성공한 음악 간의 연결 고리를 찾아 소비층의 선호도와 트랜드를 분석할 수 있습니다.**
  
  **2. 스트리밍에 영향을 주는 요소를 찾아내어 향후 음악 사업의 성공에 기여 할 수 있습니다.**

# 데이터셋 개요

| **컬럼명**                  | **설명**                                        |
|-----------------------------|-------------------------------------------------|
| `track_name`(노래 제목)     | 노래의 제목                                     |
| `artist(s)_name`(아티스트 이름) | 노래를 부른 아티스트의 이름(들)                   |
| `artist_count`(아티스트 수) | 노래에 기여한 아티스트의 수                      |
| `released_year`(발매 연도)  | 노래가 발매된 연도                               |
| `released_month`(발매 월)   | 노래가 발매된 월                                |
| `released_day`(발매 일)     | 노래가 발매된 날짜                               |
| `in_spotify_playlists`(스포티파이 플레이리스트 수) | 해당 노래가 포함된 스포티파이 플레이리스트의 수 |
| `in_spotify_charts`(스포티파이 차트 순위) | 스포티파이 차트에서의 존재 여부 및 순위             |
| `streams`(스포티파이 스트리밍 수) | 스포티파이에서의 총 스트리밍 수                    |
| `in_apple_playlists`(애플 뮤직 플레이리스트 수) | 해당 노래가 포함된 애플 뮤직 플레이리스트의 수    |
| `in_apple_charts`(애플 뮤직 차트 순위) | 애플 뮤직 차트에서의 존재 여부 및 순위              |
| `in_deezer_playlists`(디저 플레이리스트 수) | 해당 노래가 포함된 디저 플레이리스트의 수          |
| `in_deezer_charts`(디저 차트 순위) | 디저 차트에서의 존재 여부 및 순위                   |
| `in_shazam_charts`(샤잠 차트 순위) | 샤잠 차트에서의 존재 여부 및 순위                   |
| `bpm`(비트 퍼 미닛)         | 노래의 템포를 나타내는 분당 비트 수                |
| `key`(키)                   | 노래의 키(조성)                                  |
| `mode`(모드)                | 노래의 모드(메이저 또는 마이너)                  |
| `danceability`(댄스 적합도) | 노래의 댄스 적합성  |
| `valence`(밝기)           | 노래의 음악적 내용의 긍정성     |
| `energy`(에너지)          | 노래의 에너지 수준             |
| `acousticness`(어쿠스틱 정도) | 노래의 어쿠스틱 사운드 양     |
| `instrumentalness`(연주 정도) | 노래의 연주 콘텐츠 양        |
| `liveness`(라이브 요소)   | 라이브 퍼포먼스 요소의 존재      |
| `speechiness`(말하는 정도) | 노래에서 말하는 단어의 양      |

# 팀원 및 역할

[김가람](https://github.com/Ria-garam): 스트리밍 수가 높은 곡들 간에 음악적 요소 공통점이 있을 것이라고 가정, 스트리밍 상위 100위 곡들의 연관성 높은 요소 상관 관계 분석

[박현서](https://github.com/hyunse21): Spotify 내 상위 100개의 곡들을 월과 요일로 나누어 분석, 이를 통해 곡의 흥행과 연관되는 스트리밍과 관련된 요소 분석

[백승훈](https://github.com/spacerwhite): 장르별 인기 요소 분석, 음악적 특성의 패턴이 비슷한 데이터들로 클러스터링하여 장르를 예측하고, 클러스터별 인기 요인 분석

# 파일 설명

[Python_EDA_project](https://github.com/spacerwhite/spotify_EDA/blob/main/Python_EDA_project.ipynb): EDA 분석 Notebook

[Report](https://github.com/spacerwhite/spotify_EDA/tree/main/Report): 분석 보고서, ppt
