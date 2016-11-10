---
layout: page
title: Dell Precision T7600 구매
---

개인 프로젝트 수행 용도로 Dell Precision T7600을 (중고로 아주 싸게!) 구입 하였다.  
2013년 6월에 생산 된 제품으로, Core는 [Intel Xeon E5-2680](http://ark.intel.com/ko/products/64583/Intel-Xeon-Processor-E5-2680-20M-Cache-2_70-GHz-8_00-GTs-Intel-QPI) 2개가 꽂혀 있다.   
아무리 몇 세대 전의 cpu라고는 하지만 cpu당 8개의 core가 있으니 총 32개의 Thread가 돌아갈 수 있으므로 왠만한 회사에서 사용되는 Workstation 보다 나을 것이다.  
(실제로 현재 회사에서 쓰는 것보다 좋다!)

RAM은 (DDR3인게 마음이 안좋지만) 40GB이므로 개인 프로젝트를 수행하기엔 충분하다.  
거기에 Nvidia GTX 1060 6GB를 꽂아서 딥러닝 계산 작업을 돌리고 있다.  
(아래에 스크린샷에도 2개의 process가 돌고 있는 것을 볼 수 있다.)  
또한, power가 1300W나 되기 때문에, 추후에 더 많은 VGA를 꽂을 예정이다. - 특히 Titan X

이 밖에도 Hadoop, Hive를 설치해서 Query 작업도 수행 가능하다.  
Memory를 더 늘려서 Tez로도 돌려보고 싶다.

#### 단점이라면 ####
델에서 출시 된 기성품이다보니 (T7600만의 문제일 수도 있지만) Cooling이 약한 듯 하다.  
물론 중고품의 한계일 수도 있지만, 뜯어보고 먼지도 다 털어내고, fan도 정상 작동 중인데도 CPU 온도가 높다.  
Xeon의 한계 온도가 높은 편이긴 하지만, idle 시에도 60도 근처이고, full-load이면 90도를 넘나든다.  
당장은 겨울로 가는 계절이기 때문에 큰 문제가 되지 않지만, 여름이 걱정이다.  
아무래도 에어컨이 빵빵한 서버실에 둘 리 없는 개인용이기 때문에 여름이 되면 치명적일 수 밖에 없다.  
조만간 cooler 쪽을 튜닝(또는 업그레이드) 해야 하지 않을까.    

그리고 Case가 겉으로 보기에는 굉장히 큰데 불구하고  
메인보드 뒷 편에 파워서플라이와 HDD가 위치하기 때문에 케이스를 다 쓰지 못하여 두꺼운 VGA를 꽂을 수가 없다.  
따라서 VGA를 고를 때에도 신중하게 골라야 한다. (아무래도 OC 제품은 어렵다.)

#### 그래도! ####
화면 꽉 차는 core를 보면 마음이 full-fill 된다.

![nvidia-smi]({{ site.baseurl }}/img/nvidia-smi.png)

![cpuinfo]({{ site.baseurl }}/img/e5-2680_cpuinfo.png)

![top]({{ site.baseurl }}/img/e5-2680.png)
