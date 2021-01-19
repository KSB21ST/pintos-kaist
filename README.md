Brand new pintos for Operating Systems and Lab (CS330), KAIST, by Youngjin Kwon.

The manual is available at https://casys-kaist.github.io/pintos-kaist/.

##Project1
1. 우선 home 에 있는 .bashrc 파일에 


`export PATH="$PATH:/home/ksb21st/subin/pintos-kaist/utils"`

`export PATH="$PATH:/home/ksb21st/subin/pintos-kaist/source ./activate"`


를 파일의 맨 끝에 추가해주었다. $~/pintos-kiast/ 에 매번 source ./activate 를 입력해주는 수고를 덜기 위해서.

2. 그 다음에는 ~/pintos-kaist/threads$ 에서 make를 해주어야 한다. 그럼 /build 디렉토리가 생긴다

3. build 디렉토리에서 시험 삼아 ~/build$ pintos -- run alarm-multiple 를 시험삼아 해준다. 잘 되면 실행이 죽 된다