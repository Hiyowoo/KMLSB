대한민국 4단계 행정구역 + 지하철 분리형 지도 (v2)

1. 이 폴더에 있는 index.html, GeoJSON 4개, JSON 2개를 함께 보관하세요.
2. Android Termux: cd ~/storage/downloads/korea_metro_external_files_v2_261026
   python -m http.server 8765 --bind 127.0.0.1
3. 브라우저: http://127.0.0.1:8765/
4. PC VS Code Live Server도 동일하게 사용 가능합니다.

개선: 지하철 먼저 표시, 사이드 패널 숨김/펼침, 호선 필터 검색, 행정경계 호버/선택 레이어 클릭 우선순위.
외부 서버로 개인 지도 데이터를 전송하지 않습니다. 인터넷은 Leaflet/OSM 타일에 필요합니다.
