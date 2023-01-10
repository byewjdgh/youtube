# 핫도그 알고리즘

오늘은 핫도그 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

핫도그 빵을 찾기 힘들어서 크루아상을 이용해 핫도그 만들어보겠습니다.
 
### Prerequisites

핫도그 요리를 위한 기본적인 준비물입니다.

#### 핫도그 식재료

```
소세지
```
```
식용유
```
```
양파
```
```
케첩
```
```
옐로우 머스타드
```
```
버터
```
```
체다치즈
```
```
우유
```

##### 조리도구

```
팬
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

#### 커트러리

```
손
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단한 한끼입니다. 그래도 정리는 하고 시작해주세요.
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

#### 소세지 굽기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

소세지 넣기
```
tools.pot.pour(ingredients.sausage);
```

굽기
```
tools.pot.roast();
```

불 끄기
```
cooking.turnOffFire();
```

#### 치즈 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

버터 넣기
```
tools.pan.pour(ingredients.butter);
```

우유 넣기
```
tools.pan.pour(ingredients.milk);
```

체다치즈 넣기
```
tools.pan.pour(ingredients.cheddarCheese);
```

젓기
```
tools.pan.stir();
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

크루아상 올리기
```
tools.dish.stack(ingredients.croissant);
```

양파 올리기
```
tools.dish.stack(ingredients.onion);
```

소세지 올리기
```
tools.dish.stack(ingredients.sausage);
```

치즈소스 올리기
```
tools.dish.stack(cheddarCheeseSauce);
```

케첩 올리기
```
tools.dish.stack(ingredients.ketchup);
```

머스타드 올리기
```
tools.dish.stack(ingredients.mustard);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

간단한 요리였습니다. 정리잘해주세요.

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
