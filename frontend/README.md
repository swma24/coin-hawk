# Coin Hawk Frontend

SvelteKit을 기반으로 한 Coin Hawk 프로젝트의 프론트엔드입니다.

## 기술 스택

- **SvelteKit** 2.22.0 - 풀스택 웹 프레임워크
- **Svelte** 5.0 - 리액티브 UI 프레임워크
- **TypeScript** - 타입 안전성
- **Vite** - 빠른 개발 서버 및 빌드 도구
- **pnpm** - 패키지 매니저

## 개발 환경 설정

의존성을 설치합니다:

```bash
pnpm install
```

개발 서버를 시작합니다:

```bash
pnpm dev

# 또는 새 브라우저 탭에서 앱을 열려면
pnpm dev -- --open
```

## 빌드

프로덕션 버전을 빌드합니다:

```bash
pnpm build
```

프로덕션 빌드를 미리보기할 수 있습니다:

```bash
pnpm preview
```

## 개발 도구

타입 체크를 실행합니다:

```bash
pnpm check

# 또는 watch 모드로
pnpm check:watch
```

## 배포

배포를 위해서는 대상 환경에 맞는 [어댑터](https://svelte.dev/docs/kit/adapters)를 설치해야 할 수 있습니다.

현재 `@sveltejs/adapter-auto`를 사용하고 있어 대부분의 플랫폼에서 자동으로 감지됩니다.
