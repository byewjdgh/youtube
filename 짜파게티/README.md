# 짜파게티 알고리즘
오늘은 짜파게티 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

누구에게나 **시작은 어렵고 쉬운것은 없다** 생각합니다.<br>
오늘은 처음오신 누구나 따라할 수 있도록 대한민국 국민이면 한번쯤은 먹어봤을 라면을 준비했습니다.<br>
아래 내용을 차근차근 읽으시고 따라하신다면 요리에 조금 더 흥미가 붙을 것이라 생각됩니다.
시작하겠습니다.

### Prerequisites

짜파게티 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
라면 끓일 물, 한모금 마실 물
```
```
젓가락
```
```
짜파게티 한봉지
```
```
함께먹을 파김치(optional)
```
이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

모든 변수를 선언함에 있어 초기화는 필수인것 처럼, 요리 또한 초기화가 필요합니다.

나의 요리 다짐, 싱크대 청소 및 요리에 쓰일 조리 도구 청소
```
me      = Person.getInstance().cleanMind();
cooking = Cooking.getInstance().cleanSinkAndTool();
tools   = cooking.getTool();
```

재료 준비
```
ingredients = cooking.readyIngredients();
```

### Cooking

모든 변수가 초기화 되었으니 요리를 시작하시면됩니다.

냄비에 물 붓기
```
tools.pot.pour(ingredients.water);
```

불 켜기
```
cooking.turnOnFire();
```

컵에 한 모금 마실 물과 분말 스프 젓가락으로 풀기
```
dissolvedSoup 
= tools.cup.pour(
    ingredients.water, 
    ingredients.soup, 
    tools.chopsticks
);
```

물이 끓을때 까지 기다리기
```
while(!tools.pot.isBoiled){
    me.wait();
}
```

불 끄기(optional)
```
cooking.turnOffFire();
```

물 전부 버리기
```
tools.pot.empty();
```

냄비에 풀어진 스프 넣기
```
tools.pot.pour(dissolvedSoup);
```

불 켜기
```
cooking.turnOnFire();
```

풀어진 스프가 원하는 농도가 될때까지 볶기
```
while(!me.isSatisfy){
    me.Stirfry();
}
```

불 끄고 향미유 넣기
```
cooking.turnOffFire();
tools.pot.pour(ingredients.oil);
```

### Eating

맛있게 먹기
```
if(ingredients.greenOnionKimchi){
    me.eatWithKimchi();
}else{
    me.eat();
}
```

### Cleaning

여러 프로그래밍언어들은 사용하지 않는 메모리에 대해 일정주기에 따라 자동적으로 메모리 주소를 초기화 시킵니다. 하지만 현실에선 본인이 해야하겠죠?<br>
맛있게 드셨다면 사용하신 모든 도구들을 청소하고 정리하시면 됩니다.

```
cooking.cleanSinkAndTool();
```


## Built With

* [집] - 촬영 장소
* [유튜브](https://www.youtube.com/@wjdgh) - 업로드 사이트
* [고프로, 쇼티](https://gopro.com/ko/kr/) - 촬영장비

## Contributing

* [쩜식당](https://www.youtube.com/@wjdgh) - 구독 부탁드립니다.

## Authors

* **Jeongho Choi**
