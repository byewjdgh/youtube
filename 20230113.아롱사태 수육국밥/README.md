# 아롱사태 수육국밥 알고리즘

오늘은 아롱사태 수육국밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

집 근처에 맛있는 아롱사태 국밥집이 있습니다. 아롱사태 수육국밥 만들어보겠습니다.
 
### Prerequisites

아롱사태 수육국밥 요리를 위한 기본적인 준비물입니다.

#### 아롱사태 수육국밥 식재료

```
소 아롱사태
```
```
대파
```
```
양파
```
```
월계수 잎
```
```
통후추
```
```
마늘
```
```
페퍼론치노
```
```
치킨스톡 분말
```
```
물
```

##### 조리도구

```
중화팬
```
```
냄비
```
```
칼
```
```
도마
```
```
접시
```
```
집게
```
```
숟가락
```

#### 커트러리

```
숟가락
```
```
젓가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

대체적으로 삶는 요리는 간단합니다. 그래도 정리는 하고 시작해주세요.
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

#### 불순물 제거

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

아롱사태 넣기
```
tools.pot.pour(ingredients.beefShank);
```

10분간 끓이기
```
tools.pot.boil(10, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 아롱사태 수육국밥 만들기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

아롱사태 넣기
```
tools.pot.pour(ingredients.beefShank);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

월계수 잎 넣기
```
tools.pan.pour(ingredients.bayLeaves);
```

통후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

페퍼론치노 넣기
```
tools.pan.pour(ingredients.peperoncino);
```

치킨스톡 분말 넣기
``` 
tools.pan.pour(ingredients.chickenStockPowder);
```

40분간 삶기 넣기
```
tools.pan.boilDown(40, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

아롱사태 수육국밥 담기
```
tools.dish.plating(beefShankSoup);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

조금 질기진 않으신가요? 아롱사태는 최대한 얇게 썰어주셔야합니다. 정리는 꼭 해주세요.

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
