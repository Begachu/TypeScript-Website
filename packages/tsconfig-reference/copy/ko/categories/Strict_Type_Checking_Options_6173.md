---
display: "Strict Checks"
---

[컴파일러 옵션 `strict`](#strict)를 사용해 빌드 시 가능한 모든 개선점을 옵트-인하는 걸 추천합니다.

TypeScript는 광범위한 JavaScript 패턴과 기본 값을 지원해 이런 스타일을 수용하는 상당한 유연성을 가집니다.
종종 코드베이스의 안전성과 잠재적 확장성은 이런 기술 중 일부와 상충 될 수 있습니다.

다양한 JavaScript 버전을 지원하기 때문에, TypeScript를 새 버전으로 업데이트하면 두 가지 유형의 오류를 발견할 수 있습니다.

- TypeScript가 JavaScript의 이해도를 개선해 발견한 코드베이스에 이미 존재했던 오류들.
- 새로운 문제 영역을 다루는 새로운 오류 모음.

일반적으로 TypeScript는 후자의 오류 집합에 대한 컴파일러 플래그를 추가하며, 기본적으로 비활성화됩니다.
