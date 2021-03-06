[LZMA](LZMA.md) [비손실 압축 알고리즘](%EB%B9%84%EC%86%90%EC%8B%A4%20%EC%95%95%EC%B6%95%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.md)의 개량 버전

[LZMA](LZMA.md) 알고리즘이 압축율은 매우 높지만, 멀티코어를 활용할 수 없다는 단점을 보완하기 위해서 약간 개선된
알고리즘이다. 멀티코어 활용이 목적이기 때문에 압축율은 LZMA 와 거의 차이가 없다.

이 압축 알고리즘을 이용하면 압축할 데이터를 여러개로 쪼개서 동시에 병렬로 압축을 할 수 있기 때문에 현재의 멀티코어 CPU에서 압축속도를
크게 향상 시킬 수 있다. (예를 들어서 4개의 코어를 가진 시스템에서 4개의 쓰레드로 압축을 할 경우, 디스크 I/O만 받쳐준다면 싱글
쓰레드로 압축을 할 때보다 3배 이상 빠르게 압축하는게 가능하다.)

다만, [LZ77](LZ77.md) 알고리즘의 특성상 압축율을 떨어트리지 않고 압축하기 위해서는 압축하는데 필요한 메모리 사용량이
쓰레드 개수만큼 늘어나게 된다. 예를 들어 LZ77 용 사전의 크기를 4GiB 지정하고, 압축 쓰레드를 4개로 지정한 경우, 16GiB
이상의 메모리가 필요하다.

