# stm_register
```
stm32에서 사용하는 레지스터들을 공부하고 기록하는 곳
```


***


## BSRR 
BSRR 총 32비트로 이루어진 레지스터이며 SET 과 RESET 모두 명령을 내릴 수 있는 레지스터  

해당 레지스터의 0-15비트를 SET시키면 해당 레지스터에 SET을 반환,  
16-31비트는 RESET 만약 GPIO_Port->BSRR = 0x20002000;(13번핀 셋, 리셋 동시) 했다면 BSRR은 SET에 우선순위기 때문에 13번핀 SET으로 동작
## BRR
리
## ISR
