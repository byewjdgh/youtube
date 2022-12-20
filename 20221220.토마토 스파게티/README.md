# 토마토스파게티 알고리즘

오늘은 토마토스파게티 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

집에 방울토마토가 있어 방울토마토와 하인즈케첩을 이용한 토마토 스파게티를 만들어보겠습니다.
 
### Prerequisites

토마토스파게티 요리를 위한 기본적인 준비물입니다.

#### 식재료

```
물
```
```
방울토마토
```
```
마늘
```
```
엑스트라 버진 오일
```
```
후추
```
```
치킨스톡
```
```
스파게티니
```
```
페퍼론치노
```
```
하인즈 케첩
```
```
파르지아노 레지아노 치즈(optional)
```
```
관자(optional)
```
##### 조리도구

```
냄비
```
```
칼
```
```
집게
```
```
치즈 그레이터
```
```
국자
```
```
접시
```
#### 커트러리

```
숟가락
```
```
포크
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

요리전에는 깨끗하게 준비해주시고 시작해주세요.
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

요리 시작하겠습니다.

냄비에 물 붓기
```
tools.pot.pour(ingredients.water);
```

불 켜기
```
cooking.turnOnFire();
```

물이 끓을때 까지 기다리기
```
while(!tools.pot.isBoiled){
    me.wait();
}
```

치킨스톡 넣기
```
tools.pot.pour(ingredients.chickenStock);
```

스파게티니 넣기
```
tools.pot.pour(ingredients.spaghettini);
```

면이 익을때 까지 기다리기
```
while(!ingredients.spaghettini.isCooked){
    me.wait();
}
```

불 켜기
```
cooking.turnOnFire();
```

엑스트라 버진 오일 넣기
```
tools.pot2.pour(ingredients.oliveOil);
```

마늘 및 페퍼론치노 넣기
```
tools.pot2.pour(ingredients.galric, ingredients.peperoncino);
```

관자 넣기(optional)
```
tools.pot.pour(ingredients.scallops);
```

화구 변경
```
cooking.changeFire();
```

면 넣기
```
tools.pot2.pour(ingredients.spaghettini);
```

방울토마토 넣기
```
tools.pot2.pour(ingredients.cherryTomato);
```

면수 넣기
```
tools.pot2.pour(ingredients.stockSoup);
```

하인즈 케첩 넣기
```
tools.pot2.pour(ingredients.ketchup);
```

방울토마토 으깨기
```
ingredients.cherryTomato.mash();
```

관자 넣기(optional)
```
tools.pot2.pour(ingredients.scallops);
```

면을 먹고 간과 익힘 정도를 직접 확인
```
me.check(ingredients.spaghettini);
```

방울토마토 껍질제거
```
ingredients.cherryTomato.peeling();
```

불 끄기
```
cooking.turnOffFire();
```

후추 넣기
```
tools.bowl.pour(ingredients.pepper);
```

파르지아노 레지아노 치즈 넣기(optional)
```
tools.bowl.pour(ingredients.cheeze);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

토마토의 맛이 느껴지시나요? 케첩을 쓰는 나폴리 스파게티와 토마토를 쓰는 토마토 스파게티를 한번 믹스 해보았습니다. 다음엔 오리지널 토마토 스파게티로 해보겠습니다. 이제 정리해주시면 됩니다.

```
cooking.cleanSinkAndTool();
```


## Built With

* 집 - 촬영 장소
* [유튜브](https://www.youtube.com/@wjdgh) - 업로드 사이트
* [고프로, 쇼티](https://gopro.com/ko/kr/) - 촬영장비

## Contributing

* [쩜식당](https://www.youtube.com/@wjdgh) - 구독 부탁드립니다.

## Authors

* **Jeongho Choi**
