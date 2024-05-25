![image](https://github.com/2skydev/lostark-chophago-overlay/assets/43225384/620b7418-e67f-4e9d-9bab-36bc3b85bfed)

# Lost Ark 초파고 오버레이

단순히 초파고 사이트를 불러온 뒤 창 위치를 항상 위로 고정시키는 앱입니다.
- 헤더 제거
- 스크롤 숨기기
- 항상 위로 고정
- 전체적인 크기 70%로 축소
- 다양한 크기 조정 가능 (트레이 메뉴를 통해서 가능)
- 창 위치 변경 시 추후 다시 열때 위치 기억
- 앱 자동 업데이트

> 앱에 인증서를 안넣어서 설치 프로그램 실행 시 경고 문구가 표시됩니다, 무시하고 설치 진행해주세요!

## 다운로드 및 설치하기

1. 우측에 있는Releases를 클릭하거나 바로 밑에 표시되는 최신 버전 클릭
![image](https://github.com/2skydev/lostark-chophago-overlay/assets/43225384/fadf7a6f-5be0-4364-9e93-95714a4a0145)
2. `chophago-overlay-{version}.exe` 파일 다운로드
![image](https://github.com/2skydev/lostark-chophago-overlay/assets/43225384/d5fdeb10-4e96-4f68-9e73-c38d7b8ff071)
3. 다운로드한 파일 실행 (자동 설치)
4. 추후 앱 실행 시 `chophago overlay` 라는 이름으로 찾을 수 있습니다

<br/>

## Architecture

> [Figma link](https://www.figma.com/board/BGt9EJBWBnjcPCvKgEeES3/electron-nestjs-react-vite-template?node-id=304-58&t=NB3gHvd2vgOlaHfb-1)

![image](https://github.com/2skydev/electron-nestjs-react-vite-template/assets/43225384/ac40caf1-9840-480f-8352-be3e573226f0)

## Github workflow

> [Figma link](https://www.figma.com/board/BGt9EJBWBnjcPCvKgEeES3/electron-nestjs-react-vite-template?node-id=304-58&t=NB3gHvd2vgOlaHfb-1)

![image](https://github.com/2skydev/electron-nestjs-react-vite-template/assets/43225384/aa9301fe-a6d9-4075-b5bc-4126dbc03e1a)

<br/>

## Getting started

#### dev mode

```bash
pnpm dev
```

#### vite & electron build

```bash
pnpm build
```

## known error

- [%1 is not a valid Win32 application](https://github.com/pnpm/pnpm/issues/5638#issuecomment-1327988206)
- Github Action
  - Update package.json version
    - `pathspec 'dev' did not match any file(s) known to git`
      - DO: create `dev` branch from `main`
