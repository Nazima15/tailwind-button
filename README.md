# Tailwind 버튼 예제

이 프로젝트는 Tailwind CSS로 만든 간단한 버튼 컴포넌트입니다.

## 버튼 특징

- 파란색 배경과 흰색 텍스트
- 마우스 오버 시 배경색과 그림자 변경
- 클릭 시 눌린 효과 적용
- 키보드 포커스 시 링 효과 포함
- 둥근 모서리와 부드러운 색상 전환 애니메이션

## 사용된 Tailwind 클래스 설명

| 클래스명                     | 설명                      |
|--------------------------|-------------------------|
| bg-blue-600              | 버튼 기본 배경 파란색            |
| text-white               | 버튼 글자 흰색                |
| px-6 py-3                | 좌우 1.5rem, 위아래 0.75rem 패딩  |
| rounded-lg               | 둥근 모서리                   |
| shadow-md                | 기본 그림자                   |
| hover:bg-blue-700        | 마우스 오버 시 더 진한 파란색 배경  |
| hover:shadow-lg          | 마우스 오버 시 그림자 강화          |
| active:bg-blue-800       | 클릭 시 더 진한 파란색 배경         |
| active:shadow-inner      | 클릭 시 내부 그림자 효과           |
| transition-colors duration-300 ease-in-out | 부드러운 색상 전환 애니메이션       |
| focus:outline-none       | 포커스 시 기본 외곽선 제거           |
| focus:ring-4 focus:ring-blue-300 | 포커스 시 파란색 링 효과             |

## 실행 방법

1. 이 저장소를 클론하거나 다운로드합니다.
2. `index.html` 파일을 브라우저로 열어 버튼을 확인합니다.

---
