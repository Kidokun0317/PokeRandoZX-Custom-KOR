# PokeRandoZX Custom KOR

이 프로젝트는 포켓몬 게임의 진화 조건 및 아이템을 수정하는 커스텀 랜덤라이저입니다.

## 주요 기능
- 모든 포켓몬 1레벨 진화
- 최종진화는 더 이상 진화하지 않음
- 메가스톤 → 상처약, 두 번째 메가스톤 → 몬스터볼
- NDS/3DS 플랫폼 분기 UI 포함 (Java Swing)

## 빌드 방법
```bash
javac -d bin src/*.java
jar cfe PokeRandoZX.jar Main -C bin .
```
