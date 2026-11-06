# 20262R0136COSE34102

# Operating System
운영체제에 관한 학습 내용을 정리한 저장소입니다.

## Introduction
운영체제(Operating System)는 컴퓨터의 하드웨어 자원을 관리하고 사용자와 응용 프로그램이 컴퓨터를 효율적으로 사용할 수 있도록 지원하는 시스템 소프트웨어입니다.

운영체제의 주요 역할에는 프로세스 관리, 메모리 관리, 파일 시스템 관리, 입출력 장치 관리 등이 있습니다.

### Process Management

프로세스(Process)는 실행 중인 프로그램을 의미합니다.

운영체제는 여러 프로세스가 CPU를 효율적으로 사용할 수 있도록 관리합니다.

주요 개념은 다음과 같습니다.

Process State: 프로세스는 생성, 준비, 실행, 대기, 종료 등의 상태를 가집니다.

CPU Scheduling: 여러 프로세스 중 CPU를 사용할 프로세스를 결정합니다.

Context Switching: CPU에서 실행 중인 프로세스를 다른 프로세스로 전환하는 과정입니다.

### Memory Management

메모리 관리는 프로그램 실행에 필요한 메모리 공간을 할당하고 회수하는 운영체제의 기능입니다.

주요 개념은 다음과 같습니다.

Memory Allocation: 프로세스에 필요한 메모리 공간을 할당합니다.

Virtual Memory: 프로세스에 독립적인 가상 주소 공간을 제공합니다.

Paging: 가상 메모리와 물리 메모리를 일정한 크기의 페이지와 프레임 단위로 관리합니다.

Page Fault: 필요한 페이지가 현재 물리 메모리에 없을 때 발생합니다.

### File System Management

파일 시스템 관리는 데이터를 파일과 디렉터리 형태로 저장하고 관리하는 운영체제의 기능입니다.

주요 개념은 다음과 같습니다.

File Management: 파일의 생성, 읽기, 쓰기, 삭제 등의 작업을 관리합니다.

Directory Management: 파일을 계층적인 디렉터리 구조로 구성하고 관리합니다.

File Permissions: 사용자별로 파일에 대한 접근 권한을 설정하고 관리합니다.

Disk Space Management: 저장 장치의 공간을 효율적으로 할당하고 사용 가능한 공간을 관리합니다.

### I/O Device Management