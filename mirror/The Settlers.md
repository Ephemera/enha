[The Settlers 시리즈](The%20Settlers%20%EC%8B%9C%EB%A6%AC%EC%A6%88.md)의 모토를
만들게 된 기원

The Settlers라는 이름보다 Serf City라는 이름으로 더 잘 알려져 있다.`[1]` 93년 코모도 사의
[Amiga](Amiga.md)로 출시 그후 94년에 PC로 출시되었다.

![http://upload.wikimedia.org/wikipedia/en/4/4e/Settlers-
uae.png](http://upload.wikimedia.org/wikipedia/en/4/4e/Settlers-uae.png)

[[PNG external image]](http://upload.wikimedia.org/wikipedia/en/4/4e/Settlers-
uae.png)

아미가 플렛폼으로 나온 당시 세틀러

![http://upload.wikimedia.org/wikipedia/en/1/1b/The_Settlers_SVGA.png](http://
upload.wikimedia.org/wikipedia/en/1/1b/The_Settlers_SVGA.png)

[[PNG external
image]](http://upload.wikimedia.org/wikipedia/en/1/1b/The_Settlers_SVGA.png)

이후 SVGA가 적용되에 PC로 컨버팅된 세틀러

나무 -> 목공소나 석탄 + 철 -> 도구, 무기 생산 밀 재배 -> 밀가루 -> 빵 같은 산업 시스템이나 길을 닦아 물자이동, 초소를
이용한 영역 넓히기 등등 시스템의 대부분이 이때부터 이미 완성이 되어있었다. 이런 게임성과 (당시기준으로)미려한 그래픽, 코믹하고
아기자기함으로 많은 인기를 얻었다.  
참고로 일꾼들의 AI가 썩 좋지 않았던 까닭에 시간이 지나고나면 물류체계가 완전히 마비되는
[안습](%EC%95%88%EC%8A%B5.md)한 상황이 벌어지곤 하였다. 사실 플레이어가 길을 잘못닦은 탓도 있다.

위에서 지칭한 물류체계의 마비 현상은 플레이어가 물류를 고려하지 않았기 때문에 생겨나는 문제였다. 일꾼들의 AI는 명확하고 확실하게 작동하며
이러한 마비현상을 보안하기 위한 방안까지 마련해두었다. 기본적으로 하나의 길에 옮겨야 하는 자원이 많이 쌓여져 있는 경우 자동으로 두명의
일꾼이 배치되어 자원을 운반하게끔 디자인 되어있으며 이와는 별도로 병목현상이 있을 경우 다른 경로를 탐색하여 운반하도록 했다. 이것으로도
부족하다 싶었는지 일꾼이 옮길 자원의 우선순위를 지정하는 옵션을 따로 마련해 두었다. 일꾼들의 AI는 무척이나 정교하게 짜여져 있다.

왜 이런 현상이 일어나는 가에 대해서 길게 지칭해보자면 자원을 운반하는 일꾼들의 이동속도가 길이 놓여있는 지형의 고저차에 따라 현저한 차이를
보였기 때문이다. 평평한 평지와 급경사에서 일꾼의 이동속도가 3~4(주관적인 체감상 수치이다. 정확한 수치는 수정바람)배까지 차이가 났으며
이를 고려하지 않고 길을 생성할 경우 쉽게 병목현상이 발생했다.

이러한 병목현상은 특히 광산지역의 경우에서 자주 발생되었는데 이는 광산의 특성상 산지에 위치했기에 일꾼의 자원 운반 속도가 무척이나 느렸던
반면, 광산의 생산속도는 무척 높아 - 철광 하나와 탄광 하나로 제철소 두개와 대장간 두개를 돌릴 수 있을 정도 - 쉽게 자원이 쌓였기
때문이다. 실제로 운반가능한 물류의 양을 고려하지 않고 한번에 너무 많은 광산을 운영할 경우, 넘쳐나는 철광석, 석탄들로 인해 주변일대의
물류망은 순식간에 마비에 이르고 위에서 언급했듯 AI가 다른 경로 탐색을 지속적으로 실시하다보니 AI가 뒤떨어져 보이는 것이었다. 실제로 잘
정비된 물류망에서도 하나의 산지에서 효율 좋은 철광 하나와 탄광 하나, 이렇게 두개의 광산 정도만 운용해도 살짝 부하가 걸린다. 철광 2개와
탄광 2개를 운용하며 위에서 말한 마비현상을 피하기 위해선 제철소의 수를 늘리던가, 깃발을 조절하던가, 물자 운반 경로를 나눈다던가 하는
식의 고려가 필요하다.

\- 실제로 광산의 채광량이 모두 떨어져 자원이 생산이 되지 않는 시점에서 시간이 흐르면 병목현상이 자연스럽게 줄어들다 사라지는 것을 확인할
수 있다.

따라서 마비는 유저의 고려와 행동에 따라 피할 수 있는 문제이며 AI의 문제가 아니라고 할 수 있다.

후속작인 새틀러2의 경우, 1. 일꾼의 이동속도 자체가 높아졌고 2. 지형 고저차에 따른 이동속도 패널티는 1편 기준으로 봤을때 거의
없다시피 완화되었으며 - 지형을 고려해 돌아가는 길을 생성할 이유가 없어져버릴만큼 - 3. 당나귀라는 물자운반속도 증대 자원이 추가된 데다,
4. 여기에 더해 광산 개발이 가능한 산지의 면적을 크게 줄이고 5. 광산 건설에 필요한 요구면적까지 확대시킴으로써 "마비" 라고 표현될만큼
문제가 나타나지 않도록 수정했기 때문이지, 병목현상을 마음 먹고 일으킬 경우 1편과 별반 다를바 없는 모습을 보여준다.

이는 2배속 옵션과 함께 멀티플레이라는 측면을 부각시키고자 고려되었다고 예상한다.

용량도 상당히 작았다. 3.5인치 디스켓 한 장에 모두 들어가는 용량이었다.

실제 PC 정품 버젼 역시도 3.5인치 디스켓 한장이었다.

게임 제작에는 [SSI](SSI.md) 사가 지원했다.

`\----`

  * `[1]` 독일판 원제는 'Die Siedler'. 일반적으로 'The Settlers'라는 영어 번역 제목으로 알려져있는데 미국에서는 SSI가 유통을 맡으면서 제목을 'Serf City'로 바꾸었다. 국내에는 SSI 버전(제목만 바뀐게 아니라 오프닝 데모가 삭제되는 등 몇가지 변화가 있다.)이 들어왔기 때문에 1편 한정으로 '썹시티'로 더 많이 알려져있다. 2편 이후로는 미국에서도 '세틀러'라는 제목으로 출시됨.
