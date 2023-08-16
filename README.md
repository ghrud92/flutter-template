# flutter_template

플러터 프로젝트 세팅 및 flavor 등을 적용할 때 참고하기 위해 작성한 탬플릿

## 환경 설정

### Flutter

- [FVM](https://fvm.app/): 2.4.1
- Flutter: 3.10.5

### 빌드 타겟

- Android
- iOS
- Web

Web은 실제 프로덕트가 아니라 간단한 테스트를 위한 용도

## 탬플릿 적용 사항

### 적용된 것

1. Project initialization & FVM 버전 관리 적용
2. 앱 이름 &  번들 ID 변경

### 예정된 것

- [ ] Flavor 적용
- [ ] Firebase app distribution 적용
- [ ] Apple developer id 변경
- [ ] 스플래시 화면 적용
- [ ] 앱 아이콘 변경
- [ ] pre-push hook 을 위한 스크립트 추가
- [ ] Github Actions 적용(빌드, Firebase web hosting)

## 실행 방법

```bash
fvm flutter run
```
