

## My Projects
------

### Android 2D game &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2017년 1월 – 2017년 3월

>- 지도교수님의 Research Assistant 로서, 아동을 대상으로 한 Android 2D game 을 개발
>- 7-11세 아동의 시력향상 및 눈 운동이 되는 간단한 아동용 게임
>- 시작에서 종료까지 혼자서 3개월 소요, Unity 와 C# 을 사용
>- Unity 내부의 여러가지 component 에 대해 이해할 수 있는 기회가 되었으며 게임 설계 및 C# 사용 경험
>- 프로젝트의 팀원으로서 Agile/Scrum 기반의 개발 경험
>- [Repository](https://github.com/hshong9590/Bouncing-Frog)
>- [Power Point Presentation](https://hshong9590.github.io/report files/Presentation.pptx)


### Inverse Assembler &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016년 9월 – 2016년 12월

>- 프로젝트의 목적: 메모리의 hex code를 읽은 후, 그것을 해석하여 Assembly 명령어로 다시 바꾸는 작업 - Assembly 언어는 Motorola 68k를 사용
>- Java로 비유를 하면, object 파일(\*.class)을 가지고서 decomile을 하여 source 파일(\*.java)을 추출해내는 것과 유사한 과정
>- 시작에서 종료까지 2명의 팀원과 함께 4개월 소요, Easy68k (Assembly Simulator)을 사용
>- 프로젝트는 I/O, Op-Code, Operand 의 3부분으로 역할을 나누었으며 저는 Op-Code을 처리하는 역할을 담당. (Assembly 명령어 =  Op-Code + Operand)
>- 처음에는 8 bit 단위로 메모리를 읽었으나, 비슷한 명령어를 제대로 해독하지 못하는 문제가 발생 -> Operand를 명령어로 오인하여 생긴 문제
>- 결국, 뒤에 따라오는 메모리를 미리 체크하여 operand 여부에 대해 확인한 후, flag 을 사용하여 가변적인 범위(8 ~ 32 bit 단위)로 메모리를 읽는 방식으로 boundary 문제를 해결
>- 이 프로젝트를 통해 Assembly (68k)에 대해 깊은 이해를 하게 되었으며, 어려운 부분에 직면했을 때 대처하는 방법과 접근방식에 대해 많은 것을 생각하게 된 계기가 됨
>- [Repository](https://github.com/hshong9590/disassembler)
>- [Full Report](https://hshong9590.github.io/report files/Disassembler Project.pdf)


### Thread OS Project&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016년 6월 – 2016년 8월

>- Thread OS = Java로 쓰여진 OS Simulator
>- 프로젝트의 목적 : OS의 일부 component 가 주어지지 않은 상태에서, Java를 사용하여 구현
>- 시작에서 종료까지 2명의 팀원과 함께 3개월 소요
>- 완전히 백지상태에서 구현하는 것이 아닌, 기존의 Code에서 일부를 수정하여 완성하는 과정
>- OS의 아래 개념들에 깊은 이해를 하게 된 계기가 됨
>
  Process forking / Thread Concurrency &amp; Parallelism / Context Switching / CPU Scheduling / Process Synchronization / Deadlocks / Paging &amp; Swapping
> &nbsp;
>- [Repository](https://github.com/hshong9590/CSS-430)
>- [Full Report](https://hshong9590.github.io/report files/css430_report.pdf)


### Happy Hour Database &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016년 1월 – 2016년 3월

>- 프로젝트의 목적: Happy Hour라는 Mobile App에 사용될 Database를 구현하는 작업
>- Relational Model 및 Entity-Relationship Diagram 을 이용하여 Database 를 설계
>- 설계한 Database Table의 Normalization 을 거친 후, SQLite를 사용해 구현
>- 다양한 Query를 통해 여러가지 정보의 retrieving을 테스트
>- 시작에서 종료까지 2명의 팀원과 함께 3개월 소요
>- [Repository](https://github.com/hshong9590/HappyHourDatabase)
>- [Full Report](https://hshong9590.github.io/report files/Happy_HourReport.pdf)

### Movie Rental System &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2015년 9월 – 2015년 12월

>- 프로젝트의 목적: 동네의 영화 대여점에서 사용될 Movie Rental System을 C++을 사용하여 구현
>- 프로젝트는 Customer, Movie, Transaction, Inventory 의 4 부분으로 역할을 나누었으며 저는 Transaction 을 담당.
>- Design Pattern의 하나인 Factory method 을 사용하여 모든 Class를 생성 및 관리.
>- Hash table, Binary Search Tree, Inheritance, Virtual function 등의 여러 기본 개념에 대해 연습할 수 있던 계기가 됨
>- 시작에서 종료까지 3명의 팀원과 함께 3개월 소요
>- [Repository](https://github.com/hshong9590/MovieRentalSystem)
>- [UML Class Diagram](https://hshong9590.github.io/report files/UML Class Diagram.jpg)
