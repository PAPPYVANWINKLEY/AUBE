# AUBE · INNOMÉ 「무제」

「향수병: 네 다음 남편에게」의 인터랙티브 소개 웹사이트입니다.

## GitHub Pages

GitHub 저장소의 Settings → Pages에서 **Deploy from a branch**, **main**, **/docs**를 선택합니다.

사이트 파일은 `docs/`에 있으며 별도 빌드가 필요하지 않습니다. 이미지·동영상·OST·지도·폰트는 상대 경로로 불러옵니다.

## 로컬 확인

```sh
python -m http.server 8000 --directory docs
```

브라우저에서 `http://localhost:8000`을 열고 입장 버튼을 누르면 OST가 시작됩니다.

지도·폰트 라이선스와 출처는 `docs/assets/maps/`와 `docs/assets/fonts/`에 포함되어 있습니다.
