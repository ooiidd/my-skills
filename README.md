# My Skills

공개된 에이전트 스킬을 모아 둔 저장소입니다. 원본 스킬 내용과 폴더 구조를 유지합니다.

| 스킬 | 용도 | 원본 |
| --- | --- | --- |
| `karpathy-guidelines` | 가정 확인, 단순한 구현, 필요한 부분만 수정, 검증 가능한 목표 설정 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) |
| `planning-with-files` | 계획·발견·진행 상황을 파일에 저장하는 작업 방식 | [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) |

## 설치

```bash
npx skills add ooiidd/my-skills --skill karpathy-guidelines
npx skills add ooiidd/my-skills --skill planning-with-files
```

## 출처와 라이선스

두 스킬의 원본은 MIT 라이선스를 명시합니다. 이 저장소는 원저자의 작업을 모은 것이며, Andrej Karpathy가 직접 제작하거나 공식 배포한 스킬이라는 의미는 아닙니다.

- `karpathy-guidelines`: 원본의 `SKILL.md`에 `license: MIT`가 명시되어 있습니다. 원본에는 별도 LICENSE 파일이 없어, 라이선스 선언이 있는 원본 README를 `skills/karpathy-guidelines/UPSTREAM_README.md`에 보존했습니다.
- `planning-with-files`: 원본 MIT 라이선스 전문을 해당 스킬 폴더의 `LICENSE`에 포함했습니다.

복사한 원본 커밋은 [SOURCES.md](SOURCES.md)에 기록합니다. 각 도구의 스킬 및 훅 지원 범위에 따라 동작이 달라질 수 있습니다.
