# 김치찜 알고리즘

오늘은 김치찜 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

한국의 맛, 김치찜 만들어보겠습니다.
 
### Prerequisites

김치찜 요리를 위한 기본적인 준비물입니다.

#### 김치찜 식재료

```
돼지 앞다리살
```
```
양파
```
```
생강
```
```
대파
```
```
청양고추
```
```
된장
```
```
간마늘
```
```
김치
```
```
물
```
```
육수팩
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
포크
```
```
집게
```

#### 커트러리

```
젓가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

김치국물이 많이 튀깁니다. 잘 정리해주세요.
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

#### 김치찜 만들기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pan.pour(ingredients.water);
```

육수팩 넣기
```
tools.pan.pour(ingredients.stockPack);
```

거품 제거
```
tools.pan.remove(foam);
```

5분뒤 육수팩 건져내기
```
tools.pan.remove(ingredients.stockPack, 5, "min");
```

돼지 앞다리살 넣기
```
tools.pan.pour(ingredients.picnicShoulder);
```

거품 제거
```
tools.pan.remove(foam);
```

된장 넣기
```
tools.pan.pour(ingredients.soybeanPaste);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

김치 넣기
```
tools.pan.pour(ingredients.kimchi);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangRedPepper);
```

생강 넣기
```
tools.pan.pour(ingredients.ginger);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

40분간 졸이기 
```
tools.pan.boilDown(40, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

tools.dish.plating(braisedKimchi);

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨나요? 가지고 계신 김치가 조금 짜우시다면 김치를 씻은 후 넣어주세요. 정리하시면됩니다.

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
