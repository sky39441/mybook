## 주피터북

주피터 북을 이용한 첫 책 만들기

:::{note}
이건 노트라는데;
:::

# 소스코드 샘플

~~~java
	public void init() {
		log = LogManager.getFwkLog();
		if (!enabled) {
			log.info("["+getClass().getSimpleName()+"] disabled");
			return;
		}
		this.workerThread = new Thread(this, getClass().getSimpleName());
		this.workerThread.setDaemon(true);
		this.workerThread.start();
	}
~~~

# 샘플

1. MSA 는 성공할 수 있을까?

2. 10년후에도 MSA 광풍이 불까?

3. RemoteCall 의 비효율은?
   > 하드웨어가 발전하는 만큼을 remote call 이 오히려 까먹는건 아닌지?

4. tight 하지 않은 현대의 Monolithic
   > 현대의 차세대 어플리케이션도 이미 작게 쪼개진 아키텍처를 갖고 있고, 단위별 hotdeploy가 가능한데...이미.

5. Mission critical 업무에서 EDA 의 지연 처리는 감내할 수 있을까?
   > 모바일 뱅킹 이체 중에 센터컷 돌아가면??

6. 우리 업무 개발자님들이 잘 할 수 있을까?
   > 난 반대일세...

7. 우리 고객님들이 이 복잡도를 견뎌낼 수 있을까?
   > 그것도 반대일세...

