# 몽골리안 비프 알고리즘

오늘은 몽골리안 비프 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

P.F 창에서 먹었던 기억이 있습니다. 몽골리안 비프 만들어보겠습니다.
 
### Prerequisites

몽골리안 비프 요리를 위한 기본적인 준비물입니다.

#### 몽골리안 비프 식재료

```
소고기 척아이롤
```
```
쪽파
```
```
식용유
```
```
간마늘
```
```
진간장
```
```
황설탕
```
```
치킨스톡 분말
```

##### 조리도구

```
중화팬
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
숟가락
```
```
스패츌러
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

정리하는 하고 진행해주세요.
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

#### 척아이롤 굽기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

척아이롤 넣기
```
tools.pan.pour(ingredients.chuckEyeRoll);
```

불 끄기
```
cooking.turnOffFire();
```

#### 몽골리안 비프 만들기

불 켜기
```
cooking.turnOnFire();
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

진간장 넣기
```
tools.pan.pour(ingredients.soySauce);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

치킨스톡 분말 넣기
```
tools.pan.pour(ingredients.chickenStockPowder);
```

구운 척아이롤 넣기
```
tools.pan.pour(roastedChuckEyeRoll);
```

쪽파 넣기
```
tools.pan.pour(ingredients.chive);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

몽골리안 비프 담기
```
tools.dish.plating(mongolianBeef);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛은 어떤가요? 전 조금 부족하다 생각했습니다. 더 연구해서 다시 도전해보겠습니다. 이제 정리해주세요.

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
