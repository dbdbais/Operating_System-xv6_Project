# 운영체제 Xv6-Project

## Xv6 설명
xv6은 멀티프로세서 x86 및 RISC-V 시스템을 위한 제6판 유닉스의 ANSI C용의 현대의 재 구현체이다. MIT의 운영 체제 엔지니어링 코스의 교육 목적으로 개발. 이론적으로 배운 OS의 작동방식을 C언어로 코드를 직접 구현해 보며 결과를 확인할 수 있다.

## Project #0 [Install xv6]
가상머신 Ubuntu를 이용해 xv6 운영체제를 구동하고, 본인의 학번과 이름을 출력해 본다.

## Project #1 [System Call]
커널 공간과 사용자 공간을 이해하고, 시스템 콜을 이용해 리눅스 명령어 횟수를 세서 화면상에 띄우는 readCount를 구현하고 xv6에서 호출한다.

## Project #2 [Scheduling]
프로세스의 상태에 대해 이해하고, 프로세스에 우선순위인 nice 값을 추가해 Round-Robin 형식으로 구현된 xv6 Scheduler를 Priority-Based Scheduler로 변환한다. 테스트 케이스를 통해 올바르게 구현되었는지 확인할 수 있다.

## Project #3 [Stack Growth]
OS가 메모리를 할당할 때 사용하는 대표적인 기법인 Paging 기법을 xv6에서 메모리공간을 효율적으로 쓸 수 있게 구현한다. 기존에 구현되어 있지 않은 pageFault나 스택의 특징을 참고하여 메모리공간을 핸들링한다. 테스트 케이스를 통해 올바르게 구현되었는지 확인할 수 있다. 

## Project #4 [Copy On Write]
xv6에 여러 페이지를 같이 참조할 수 있게 페이지를 참조하는 referenceCount를 추가로 구현한다. 테스트 케이스를 통해 올바르게 구현되었는지 확인할 수 있다. 



