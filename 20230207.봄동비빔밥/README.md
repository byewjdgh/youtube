# 봄동비빔밥 알고리즘

오늘은 봄동비빔밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

홈플러스에 봄동을 팔더라구요. 봄동비빔밥 만들어보겠습니다.
 
### Prerequisites

봄동비빔밥 요리를 위한 기본적인 준비물입니다.

#### 봄동비빔밥 식재료

```
봄동
```
```
참기름
```
```
진간장
```
```
고춧가루
```
```
밥
```

##### 조리도구

```
칼
```
```
도마
```
```
믹싱볼
```
```
숟가락
```
#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단합니다. 그래도 정리는 합시다.
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

#### 봄동비빔밥 만들기

봄동 넣기
```
tools.pan.pour(ingredients.cabBage);
```

진간장 넣기
```
tools.mixingBowl.pour(ingredients.soySauce);
```

참기름 넣기
```
tools.mixingBowl.pour(ingredients.sesameOil);
```

소금 넣기
```
tools.mixingBowl.pour(ingredients.salt);
```

양파 넣기
```
tools.mixingBowl.pour(ingredients.onion);
```

밥 넣기
```
tools.mixingBowl.pour(ingredients.boiledRice);
```

섞기
```
tools.mixingBowl.mix();
```

### Plating

봄동비빔밥 담기
```
tools.dish.plating(cabBageBibimbap);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

간단하죠? 맛있더라구요. 봄동을 조금더 먹기 좋게 썰거나, 조금만 더 절여졌다면 더 맛있었을 것 같습니다. 이제 정리해주세요.

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
