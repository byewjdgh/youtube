# 바지락 스파게티 알고리즘

오늘은 바지락 스파게티 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

어제 술을 마셨더니 해장이 필요합니다. 바지락 파스타 만들어보겠습니다.
 
### Prerequisites

바지락 스파게티 요리를 위한 기본적인 준비물입니다.

#### 바지락 스파게티 식재료

```
바지락
```
```
청양고추
```
```
마늘
```
```
페페론치노
```
```
후추
```
```
엑스트라버진오일
```
```
치킨스톡
```
```
물
```
```
후추
```

##### 조리도구

```
중화팬
```
```
프라이팬
```
```
칼
```
```
도마
```
```
숟가락
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

어패류가 있으니 식중독 조심하시고, 정리를 잘해주세요.
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

#### 바지락 스파게티 만들기

불 켜기
```
cooking.turnOnFire();
```

엑스트라버진오일 넣기
```
tools.pan.pour(ingredients.extraVirginOliveOil);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

패페론치노 넣기
```
tools.pan.pour(ingredients.peperoncino);
```

바지락 넣기
```
tools.pan.pour(ingredients.manilaClam);
```

면수 넣기
```
tools.pan.pour(ingredients.cookingWater);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

면 넣기
```
tools.pan.pour(ingredients.spaghettini);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangRedPepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

바지락 스파게티 담기
```
tools.dish.plating(manilaClamSpaghetti);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

해장으로 손색이 없습니다. 이제 정리해주세요.

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
