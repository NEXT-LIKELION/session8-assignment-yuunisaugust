[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TbF52kGg)
# 과제 안내사항

## 문제 상황
Git에서 두 브랜치를 병합할 때 다음과 같은 오류가 발생할 수 있습니다: fatal: refusing to merge unrelated histories

이 오류는 두 브랜치 간에 **공통 조상 커밋이 없는 경우** 발생합니다.  
예를 들어, 서로 다른 Git 레포지토리에서 가져온 브랜치를 병합하려고 할 때 주로 발생합니다.

이 문제를 해결하려면 `--allow-unrelated-histories` 옵션을 사용하여 강제로 병합할 수 있습니다:
ex) git merge feature1 --allow-unrelated-histories

클래스룸에 레포지토리를 클래스룸에 다른 레포지토리를 추가하다보니 발생한 문제이니 안내사항 참고하셔서 병합과 conflict merge 하시면 됩니다.