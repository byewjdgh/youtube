# 마르게리타 피자 알고리즘

오늘은 마르게리타 피자 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

피자를 가장 좋아합니다. 마르게리타 피자 만들어보겠습니다.
 
### Prerequisites

마르게리타 피자 요리를 위한 기본적인 준비물입니다.

#### 마르게리타 피자 식재료

```
생 모짜렐라 치즈
```
```
또띠아
```
```
바질
```
```
엑스트라 버진 오일
```
```
토마토 소스
```
```
양파
```
```
마늘
```
```
페페론치노
```
```
드라이 로즈마리
```
```
월계수 잎
```
```
소금
```
```
후추
```
```
물
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
스패츌러
```
```
접시
```
```
블렌더
```
#### 커트러리

```
손가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

두가지를 요리를 해야합니다. 정리를 꼭 해주세요.
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

#### 토마토 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

페페론치노 넣기
```
tools.pan.pour(ingredients.peperoncino);
```

토마토 소스 넣기
```
tools.pan.pour(ingredients.tomatoSauce);
```

드라이 로즈마리 넣기
```
tools.pan.pour(ingredients.DriedRosemary);
```

월계수 잎 넣기
```
tools.pan.pour(ingredients.bayLeaves);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

월계수 잎 제거
```
tools.pan.remove(ingredients.bayLeaves);
```

40분간 끓이기
```
tools.pan.boil(40, "min");
```

불 끄기
```
cooking.turnOffFire();
```

갈기
```
tools.blender.blend(tomatoSauce);
```

#### 마르게리타 피자 만들기

불 켜기
```
cooking.turnOnFire();
```

또띠아 넣기
```
tools.pan.pour(ingredients.tortilla);
```

토마토 소스 넣기
```
tools.pan.pour(tomatoSauce);
```

생 모짜렐라 치즈 넣기
```
tools.pan.pour(ingredients.freshMozzarellaCheese);
```

바질 넣기
```
tools.pan.pour(ingredients.basil);
```

엑스트라 버진 오일 넣기
```
tools.pan.pour(ingredients.extraVirginOil);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

마르게리타 피자 담기
```
tools.dish.plating(MargheritaPizza);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

완벽한 맛입니다. 이제 정리해주세요.

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
