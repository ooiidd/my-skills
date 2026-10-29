# My Skills

Codex용으로 공개된 두 스킬을 모아 둔 저장소입니다. 각 원본의 스킬 파일을 수정 없이 복사했습니다.

| 스킬 | 용도 | 원본 |
| --- | --- | --- |
| `karpathy-guidelines` | Codex의 코딩·리뷰·디버깅 작업에서 가정 확인, 단순한 구현, 필요한 부분만 수정, 결과 검증 | [richling98/karpathy-codex-skills](https://github.com/richling98/karpathy-codex-skills) |
| `planning-with-files` | Codex의 여러 단계 작업에서 계획·발견·결과물을 Markdown 파일로 관리 | [d0ublecl1ck/planning-with-files-codex](https://github.com/d0ublecl1ck/planning-with-files-codex) |

## 설치

```bash
npx skills add ooiidd/my-skills --skill karpathy-guidelines -a codex
npx skills add ooiidd/my-skills --skill planning-with-files -a codex
```

설치 후 Codex에서 `$karpathy-guidelines` 또는 `$planning-with-files`로 호출할 수 있습니다.

## 포함된 구성

- Karpathy: Codex용 `SKILL.md`와 `agents/openai.yaml`.
- Planning: `SKILL.md`, `reference.md`, `examples.md`. 이 포크는 `task_plan.md`, `notes.md`, 결과물 파일을 사용하는 지침 기반 스킬이며 자동 훅이나 실행 스크립트를 포함하지 않습니다. 계획 파일 등을 `.gitignore`에 추가하도록 지시하는 원본 동작도 유지했습니다.

이전 범용 버전과 Planning의 스크립트·템플릿은 제거했습니다. Codex용으로 작성된 커뮤니티 스킬이며, 성능 개선을 별도로 검증했다는 의미는 아닙니다.

## 출처와 라이선스

두 스킬 모두 MIT 라이선스입니다. 각 스킬 폴더의 `LICENSE`에 원본 라이선스 전문을 포함했습니다. 원본 주소와 복사한 커밋은 [SOURCES.md](SOURCES.md)에 기록했습니다.

Karpathy 스킬은 Andrej Karpathy의 공개 관찰에서 영감을 받은 커뮤니티 작업이며, Andrej Karpathy 또는 OpenAI의 공식 배포물이라는 의미는 아닙니다.
