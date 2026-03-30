# HSC 아이디어 대시보드

## 아이디어 생성
```button
name 새 아이디어 생성
type command
action Templater: Create new note from template
```

---

## 전체 아이디어
```dataview
table file.name as 이름, 점수
from "HSC/Ideas"
sort 점수 desc
```

---

## 해야 할 일 (전체)
```tasks
not done
path includes HSC/Ideas
```

---

## 상태 기준
- #status/idea → 기본 아이디어
- #status/dev → 발전 중
- #status/hold → 보류
- #status/drop → 폐기
