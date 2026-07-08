kali-linux: 공격 redteam용 vmware
id/pw: kali

ubuntu 24.04.: 방어팀용 ubuntu GUI 
id/pw:ubuntu

ubuntu cli로 변경 가능하나 편의성을 위해 gui로 테스트 후 
마무리에 cli로 테스트하는것이 낫다고 판단

# 무조건!!! settings에서 Network-Adapter를 host-only로 지정후 사용할것


ubuntu 탐지파일 실행:

```bash
	home/Packetanalyzer에서 터미널열고
	
	source $HOME/.local/bin/env

	source .venv/bin/activate

	sudo .venv/bin/python  main.py
```

외부파일(vmware 밖)을 안으로 넣고 싶을때는 cloud (git)에 저장하여서
`git clone 깃주소` 를 하여 다운받는게 가장 좋다.
drag&drop 할시 오류나 렉이 발생 

kali는 home/miniproject에 공격,스캔파일이 있다. 
Howto를 열면 명령어와 기본 실행코드가 적혀있다.


snapshot은 되도록 지양할것. (용량이 배로 커짐)
