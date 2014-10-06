# Step1. 기본 출발점

거이 모든 기본적인 프로젝트는 소스코드 파일에서 실행가능한 빌드를 만듭니다. 단순한 프로젝트들은 두라인으로 구성된 CMakeLists파일이면 충분합니다. 아래와 같은 CMakeLists파일에서 설명을 시작합니다.

```cmake
cmake_minimum_required (VERSION 2.6)
project (Tutorial)
add_executable(Tutorial tutorial.cxx)
```


