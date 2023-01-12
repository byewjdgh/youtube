# 매운갈비찜 알고리즘

오늘은 매운갈비찜 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

사나이 울리는 매운갈비찜 만들어보겠습니다.
 
### Prerequisites

매운갈비찜 요리를 위한 기본적인 준비물입니다.

#### 매운갈비찜 식재료

```
돼지갈비
```
```
생강
```
```
청양고추
```
```
홍고추
```
```
치킨스톡 분말
```
```
황설탕
```
```
양파
```
```
대파
```
```
월계수 잎
```
```
갈아만든 배
```
```
간마늘
```
```
고춧가루
```
```
후추
```
```
소금
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
블렌더
```
```
집게
```
```
국자
```
```
숟가락
```

#### 커트러리

```
손
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

할게 많습니다. 잘 정리해주세요.
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

#### 돼지갈비 삶기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

돼지갈비 넣기
```
tools.pot.pour(ingredients.porkRip);
```

10분간 끓이기
```
tools.pot.boil(10, "min");
```

불 끄기
```
cooking.turnOffFire();
```

삶은 돼지갈비 씻기
```
boiledPorkRip.clean();
```

#### 돼지갈비 염지

불 켜기
```
cooking.turnOnFire();
```

물
```
tools.pan.pour(ingredients.water);
```

치킨스톡 분말 넣기
```
tools.pan.pour(ingredients.chickenStockPowder);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

월계수 잎 넣기
```
tools.pan.pour(ingredients.bayLeaves);
```

20분간 졸이기
```
tools.pan.boilDown(20, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 매운갈비찜 만들기

불 켜기
```
cooking.turnOnFire();
```

육수 넣기
```
tools.pot.pour(ingredients.stock);
```

삶은 돼지갈비 넣기
```
tools.pan.pour(boiledPorkRip);
```

갈아만든 배 넣기(aka. ldh)
```
tools.pan.pour(ingredients.pearDrink);
```

생강 넣기
```
tools.pan.pour(ingredients.ginger);
```

홍고추 넣기
```
tools.pan.pour(ingredients.groundRedPepper);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

고춧가루 넣기
```
tools.pan.pour(ingredients.redPepperPowder);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

30분간 졸이기
```
tools.pan.boilDown(30, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

매운갈비찜 담기
```
tools.dish.plating(spicyBraisedPorkRib);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

싱겁지는 않으셨나요? 진간장이나 치킨스톡 분말을 추가하시면 더 괜찮아질겁니다. 이제 정리해주세요.

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
