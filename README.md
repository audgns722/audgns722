# Portfolio 사이트 만들기

포트폴리오를 Vue, Vite, React, next 각각의 버전으로 만들기

## 제작기간
- 2week 2023.10 30 ~ 2023. 11. 13

## Stack
<img alt="Html" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img alt="Css" src ="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white"/> <img alt="JavaScript" src ="https://img.shields.io/badge/JavaScriipt-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=black"/> ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

#### Vue 버전 🍒 [Link](https://vue-project2023-hoons.vercel.app/) 
- ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
- Vue.js는 직관적이고 가볍게 사용할 수 있는 JavaScript 프레임워크로, 양방향 데이터 바인딩과 컴포넌트 기반의 아키텍처를 특징으로 합니다. Vue CLI를 사용하면 프로젝트 생성과 관리가 용이하며, Vue Router와 Vuex 등의 공식 라이브러리들이 잘 통합되어 있습니다.
- #### 트러블 슈팅
- <details>
<summary>공백</summary>

#### 버그(해결) :
</details>

#### Vite 버전 💎 [Link](https://vite-project-2023.netlify.app/) 
- ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
- Vite는 Vue.js를 위한 빠른 개발 서버와 최적화된 빌드 도구로, 브라우저에서 동작하는 코드를 생성하며, ESM(ES Module) 기반의 빌드와 Vue 파일에 대한 효율적인 처리를 제공합니다. 빌드 속도와 효율성에 중점을 두어 현대적이고 가벼운 웹 개발을 지원합니다.
- ## 트러블 슈팅

<details>
<summary>git 업로드 버그</summary>

<!-- summary 아래 한칸 공백 두어야함 -->

## git 업로드 권한 버그(해결) :

# 권한으로 인한 업로드 버그 해결

윈도우 자격증명 > git 아이디 변경
`git remote set-url origin https://github.com@audgns722/vite-project2023.git` > `git push -u origin master`
깃헙 패스워드 입력을 하라는 창이 나오고 입력을 하시면 본인의 깃주소에 소스코드가 올라갑니다.
인증이 끝난 후부터는 git push만 하면 기존의 세팅한 주소로 바로 푸쉬가 됩니다.

</details>

<details>
<summary>Whitespace 에러</summary>

<!-- summary 아래 한칸 공백 두어야함 -->

## Whitespace 에러(해결) :

# push 중 warning

[해결!](https://velog.io/@wnguswn7/Git-Bash-warning-in-the-working-copy-of-.gitignore-LF-will-be-replaced-by-CRLF-the-next-time-Git-touches-it)  
Git의 core.autocrlf 라는 기능을 켜서 이를 자동 변환 해주도록 하면 된다.

- `git config --global core.autocrlf true` // 시스템 전체에 적용
- `git config core.autocrlf true` // 해당 프로젝트에만 적용
</details>

#### React 버전 💚 [Link](https://hoons-react-project-aaa3b.web.app/) 
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- React는 Facebook에서 만든 JavaScript 라이브러리로, 가상 DOM을 활용한 성능 최적화와 컴포넌트 기반의 UI 개발이 주요 특징입니다. Create React App을 사용하여 프로젝트를 빠르게 시작할 수 있으며, 상태 관리를 위한 Redux나 MobX와 같은 라이브러리를 선택적으로 도입할 수 있습니다.
- ## 트러블 슈팅

<details>
<summary>Whitespace 에러</summary>

<!-- summary 아래 한칸 공백 두어야함 -->

## Whitespace 에러(해결) : push 중 warning

[해결!](https://velog.io/@wnguswn7/Git-Bash-warning-in-the-working-copy-of-.gitignore-LF-will-be-replaced-by-CRLF-the-next-time-Git-touches-it){:target="\_blank"}  
Git의 core.autocrlf 라는 기능을 켜서 이를 자동 변환 해주도록 하면 된다.

- `git config --global core.autocrlf true` // 시스템 전체에 적용
- `git config core.autocrlf true` // 해당 프로젝트에만 적용
</details>

#### Next 버전 🏅 [Link](https://next-project02.vercel.app/) 
- ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
- Next.js는 React 기반의 서버사이드 렌더링(SSR) 및 정적 사이트 생성(SSG)을 지원하는 웹 프레임워크입니다. 파일 시스템 기반의 동적 라우팅과 빌트인 API 지원 등을 제공하여 React 애플리케이션을 빠르게 개발할 수 있습니다. Vercel과의 통합으로 쉽게 배포할 수 있습니다.
- ## 트러블 슈팅
<details>
<summary>ReactServerComponentsError</summary>
<!-- summary 아래 한칸 공백 두어야함 -->

## (해결) : javascript, jquery(CSR)브라우저에서 작동
- 최상단에 "use client"로 설정
`./src\app\page.js   
ReactServerComponentsError: You're importing a component that needs useEffect. It only works in a Client Component but none of its parents are marked with "use client", so they're Server Components by default. Learn more: https://nextjs.org/docs/getting-started/react-essentials 
   ╭─[C:\Users\line\Documents\GitHub\myeonghun\next-project\src\app\page.js:1:1]
 1 │ import React, { useEffect } from 'react'
   ·                 ─────────
 2 │ import Skip from '@/components/Skip'
 3 │ import Header from '@/components/Header'
 4 │ import Intro from '@/components/Intro'
   ╰────
Maybe one of these should be marked as a client entry with "use client":
./src\app\page.js`

</details>

<details>
<summary>Attempted import error</summary>
<!-- summary 아래 한칸 공백 두어야함 -->

## (해결) : Attempted import error
- `export function link()... ` -> `const link = () => ... export default link;`
`Attempted import error: '@/utils/link' does not contain a default export (imported as 'link').`

</details>

