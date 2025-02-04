
# Title<br>과제 제목


## Description<br>설명

* Description of the assignment.<br>과제에 대한 설명입니다.

## Implementation<br>구현

* Description of the implementation.<br>구현에 대한 설명입니다.

### File Table<br>파일 목록

| File or Folder<br>파일 또는 폴더 | Type<br>형식 | Purpose<br>목적 | Description<br>설명 | Permission<br>권한 |
|-----------------------|----------|---------------------------|-------------------------------------------------------------------------------------|:-------------:|
| `exercise.py`    | Python   | Main Script<br>주 파일 | Write your code to solve the assignment problem in this file.<br>이 파일에 과제 코드를 작성.  | Modify<br>수정 |
| `sample.py`           | Python   | Example Usage<br>사용 예 | This file demonstrates how to use the assignment code.<br>과제 코드 사용 예. | Read-Only<br>읽기 전용 |
| `.github/workflows/` | YAML     | CI/CD Configuration<br>연속 통합/배포 설정 | Defines automated workflows for testing and deployment.<br>시험 배포 자동화 절차 설정. | Read-Only<br>읽기 전용 |
| `tests/`              | Python   | Test Cases<br>시험 파일 | Tests to check the correctness of your code.<br>코드가 맞는지 시험. | Read-Only<br>읽기 전용 |

### Function Table<br>함수 목록

* Description of the function(s) of the `exercise.py` file.<br>`exercise.py` 파일의 함수에 대한 설명입니다.

| function<br>함수 | return type<br>반환 형 | unit<br>단위 | return value<br>반환값 |
|:--------:|:-----------:|:-----------:|:-----------:|
| `f(x0, x1)` | `float` | $m^2$ | The area of the cross-section.<br> 단면의 전체 면적. |

* Write all your code within the function(s) in `exercise.py`, but feel free to add comments outside the functions to explain your work.<br>`exercise.py` 의 모든 코드는 함수 안에 작성되어야 함. 예외로 설명을 위한 주석문은 함수 밖에 자유로이 추가할 수 있음.

### Argument Table<br>매개변수 목록

| argument<br>매개변수 | return type<br>반환 형 | unit<br>단위 | return value<br>반환값 |
|:--------:|:-----------:|:-----------:|:-----------:|
| `x0` | `float` | $m$ | The width of the cross-section.<br> 단면의 폭. |
| `x1` | `float` | $m$ | The height of the cross-section.<br> 단면의 높이. |

### Return Value Key Table<br>매개변수 키 목록

* If one (or more) of the assignment functions return a dictionary with multiple values, please describe the return value keys.<br>과제 함수 중 하나가(또는 여럿이) 여러 값을 담은 `dict`를 반환하는 경우, 반환값 키에 대해 설명하십시오.

| return value key<br>반환값 key | type<br>형 |unit<br>단위 | value |
|:--------:|:-----------:|:-----------:|:-----------:|
| `'a_moment_above'` | `float` | $m^3$ | area moment of the section above the centroid. (>0)<br>중립축 위의 면적 모멘트. (>0) |
| `'a_moment_below'` | `float` | $m^3$ | area moment of the section below the centroid. (>0)<br>중립축 아래의 면적 모멘트. (>0) |
| `'close'` | `bool` | - | whether these two area moments are close to each other?<br>두 면적 모멘트가 가까운가? |

### Allowed Modules<br>허용 모듈 목록

* In the `exercise.py` file, please `import` these modules only.<br>`exercise.py` 파일에서는 아래 모듈만 `import` 바랍니다.

| module<br>모듈 | description<br>설명 |
|:--------:|:-----------:|
| `math` | math functions<br>수학 함수 |


## Grading<br>평가

* Description of the grading.<br>평가에 대한 설명입니다.

| Criteria<br>기준	| Points<br>배점 |
|:---------:|:------:|
| Python Syntax<br>파이썬 문법	| 2 |
| Coding Style<br>모든 코드는 함수 안에	| 1 |
| Final Result<br>최종 결과	| 2 |


## Example<br>예

* Description of the example.<br>예에 대한 설명입니다.

## Notes<br>참고사항

* Additional notes.<br>추가적인 참고사항입니다.

## References<br>참고문헌

* References for the assignment.<br>과제에 대한 참고문헌입니다.

``From here is common to all assignments.``

## How to use Github web editor<br>Github 웹 편집기 사용법
* Press <kbd>.</kbd> key to start MS VS Code web editor<br><kbd>.</kbd> 키를 누르면 MS VS Code 의 Web version 이 시작됨
* Make changes to the file<br>파일을 수정
* From the left bar with the three horizontal lines at the top, (right below the magnifying glass) choose third icon, Source Control<br>왼쪽에서 줄 셋 아래 (확대경 다음) 세번째 가지치기 아이콘 선택
* Choose filename to see changes<br>변경 사항을 보려면 파일 이름 선택
* To stage changes to commit, choose + on the right side of the filename <br>수정 사항을 commit 등록 대상으로 add 추가 하려면 파일 이름의 오른쪽 + 기호 선택
* Describe the changes in the blank above<br>위 빈칸에 변경 사항 설명 입력
* Choose Commit<br>[커밋 및 푸시] 선택
* To return to the repository, use the command in the three horizontal lines<br>줄 셋 의 [리포지토리로 이동] 선택하여 저장소로 복귀

## Notes

* This assignment was developed with the assistance of an AI language model for creative inspiration and guidance, demonstrating the potential of AI as a tool to enhance learning and problem-solving.  Students are encouraged to use AI responsibly and ethically, always prioritizing their own understanding and critical thinking.

## NOTICE REGARDING STUDENT SUBMISSIONS<br>제출 결과물에 대한 알림

* Your submissions for this assignment may be used for various educational purposes. These purposes may include developing and improving educational tools, research, creating test cases, and training datasets.<br>제출 결과물은 다양한 교육 목적으로 사용될 수 있을 밝혀둡니다. (교육 도구 개발 및 개선, 연구, 테스트 케이스 및 교육용 데이터셋 생성 등).

* The submissions will be anonymized and used solely for educational or research purposes. No personally identifiable information will be shared.<br>제출된 결과물은 익명화되어 교육 및 연구 목적으로만 사용되며, 개인 식별 정보는 공유되지 않을 것입니다.

* If you do not wish to have your submission used for any of these purposes, please inform the instructor before the assignment deadline.<br>위와 같은 목적으로 사용되기 원하지 않는 경우, 과제 마감일 전에 강사에게 알려주기 바랍니다.

``Until here is common to all assignments.``
