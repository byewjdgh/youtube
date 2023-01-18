# 오야꼬동 알고리즘

오늘은 오야꼬동 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

저는 오야꼬동을 좋아합니다. 오야꼬동 만들어보겠습니다.
 
### Prerequisites

오야꼬동 요리를 위한 기본적인 준비물입니다.

#### 오야꼬동 식재료

```
닭다리살
```
```
양파
```
```
쑥갓
```
```
혼쯔유
```
```
계란
```
```
황설탕
```
```
맛술
```
```
물
```

##### 조리도구

```
돈부리팬
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

정리를 하고 요리 해주세요.
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

#### 오야꼬동 만들기

불 켜기
```
cooking.turnOnFire();
```

혼쯔유 넣기
```
tools.pan.pour(ingredients.tzuyu);
```

물 넣기
```
tools.pan.pour(ingredients.water);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

맛술 넣기
```
tools.pan.pour(ingredients.mirim);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

닭다리살 넣기
```
tools.pan.pour(ingredients.ChickenThigh);
```

끓이기
```
tools.pan.boil();
```

계란 넣기
```
tools.pan.pour(ingredients.egg);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

오야꼬동 담기
```
tools.dish.plating(oyakodon);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

저도 처음하다 보니 어색하긴하네요. 다음엔 제대로 연구해서 해보겠습니다. 이제 정리해주세요.

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
