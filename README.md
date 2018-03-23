# tmux

  설치 방법
  
  ```
  $ git clone https://github.com/tmux/tmux.git
  cd tmux
  (sudo apt-get install automake1.11)    ///없을 경우
  sh autogen.sh
  ./configure && make
  ```
  
# 종료

`(ctrl + b) d`

# 세션 다시 시작하기 

`$ tmux attach -t sesstion_number (or session_name) `

# 세션 목록 보기 (여기서 목록을 보고 꺼줘야 할 경우가 많다.)

`$ tmux ls`
