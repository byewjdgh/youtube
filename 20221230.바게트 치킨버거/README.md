# 바게트치킨버거 알고리즘

오늘은 바게트치킨버거 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

닭가슴살 모양과 컷팅된 바게트빵의 모양이 비슷하더라고요. 바게트치킨버거 만들어보겠습니다.
 
### Prerequisites

바게트치킨버거 요리를 위한 기본적인 준비물입니다.

#### 바게트치킨버거 식재료

```
박력분 밀가루
```
```
소금
```
```
후추
```
```
마늘 파우더
```
```
파프리카 파우더
```
```
계란
```
```
바게트빵
```
```
닭가슴살
```
```
식용유
```
```
버터
```
```
양상추
```
```
슬라이스 치즈
```
```
토마토
```
```
마요네즈
```
```
케첩
```
```
엘로우 머스타드
```
```
꿀
```

##### 조리도구
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
집게
```
```
블렌더
```
```
전자레인지
```
```
접시
```
```
숟가락
```
```
장갑
```

#### 커트러리

```
손
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

조리도구를 매우 많이 사용합니다. 정리를 잘해주세요.
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

#### 햄버거 소스 만들기

마요네즈 넣기
```
tools.bowl.pour(ingredients.mayonnaise);
```

케첩 넣기
```
tools.bowl.pour(ingredients.ketchup);
```

머스타드 넣기
```
tools.bowl.pour(ingredients.mustard);
```

꿀 넣기
```
tools.bowl.pour(ingredients.honey);
```

섞기
```
tools.bowl.mix();
```

#### 바게트 빵가루 만들기

바게트빵 넣기
```
tools.blender.pour(ingredients.Baguette);
```

전자레인지 1분 돌리기
```
tools.microwave.turnOn(1, "min");
```

블랜더로 갈기
```
tools.blender.blend();
```

#### 치킨 패티 만들기

밀가루 넣기
```
tools.dish.pour(ingredients.softFlour);
```

소금 넣기
```
tools.dish.pour(ingredients.salt);
```

후추 넣기
```
tools.dish.pour(ingredients.);
```

파프리카 파우더 넣기
```
tools.dish.pour(ingredients.paprikaPpowder);
```

마늘 파우더 넣기
```
tools.dish.pour(ingredients.galricPpowder);
```

계란 넣기
```
tools.dish2.pour(ingredients.egg);
```

계란 풀기
```
tools.dish2.mix();
```

바게트 빵가루 넣기
```
tools.dish3.pour(ingredients.BaguetteBreadCrumbs);
```

닭가슴살 튀김옷 입히기
```
ingredients.chickenBreast.dip(tools.dish);
ingredients.chickenBreast.dip(tools.dish2);
ingredients.chickenBreast.dip(tools.dish3);
```

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

치킨 패티 튀기기
```
tools.pot.fry(ingredients.chickenPatty);
```

불 끄기
```
cooking.turnOffFire();
```

#### 바게트 번 만들기

불 켜기
```
cooking.turnOnFire();
```

버터 넣기
```
tools.pot.pour(ingredients.butter);
```

바게트빵 넣기
```
tools.pot.pour(ingredients.baguette);
```

불 끄기
```
cooking.turnOffFire();
```
### Plating

바게트빵 올리기
```
tools.dish.stack(ingredients.baguette);
```

햄버거 소스 올리기
```
tools.dish.stack(ingredients.hamburgerSauce);
```

양상추 올리기
```
tools.dish.stack(ingredients.lettuce);
```

치킨패티 올리기
```
tools.dish.stack(ingredients.chickenPatty);
```

슬라이스 치즈 올리기
```
tools.dish.stack(ingredients.slicedCheese);
```

슬라이스 토마토 올리기
```
tools.dish.stack(ingredients.slicedTomato);
```

햄버거 소스 올리기
```
tools.dish.stack(ingredients.hamburgerSauce);
```

바게트빵 올리기
```
tools.dish.stack(ingredients.baguette);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

오랜만에 힘든 요리를 했습니다. 잘따라하셨나요? 실패해도 괜찮습니다. 다음에 또 하시면 되니까요.
정리 잘해주세요.

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
