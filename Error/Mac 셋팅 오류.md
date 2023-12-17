#### ssh git Permission denied 오류 해결 #git #ssh

vi ~/.ssh/config 파일 생성 또는 수정
```
HostkeyAlgorithms +ssh-rsa
PubkeyAcceptedAlgorithms +ssh-rsa
KexAlgorithms +diffie-hellman-group1-sha1
```


# Test
test code
```c#
public void Test()
{
}
```
