# 소고기우동 알고리즘

오늘은 소고기우동 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

추운날에는 우동아니겠습니까? 소고기 우동 만들어보겠습니다.
 
### Prerequisites

소고기우동 요리를 위한 기본적인 준비물입니다.

#### 소고기우동 식재료

```
우동면
```
```
물
```
```
대파
```
```
혼쯔유
```
```
맛술
```
```
말린 표고버섯
```
```
말린 다시마
```
```
황설탕
```
```
가쓰오부시
```
```
우삼겹
```

##### 조리도구
```
프라이팬
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
집게
```
```
그릇
```
```
체
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

우동은 생각보다 간단합니다. 하지만 정리는 해야합니다.
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

#### 우동국물 만들기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

혼쯔유 넣기
```
tools.pot.pour(ingredients.tzuyu);
```

맛술 넣기
```
tools.pot.pour(ingredients.cookingWine);
```

말린 표고버섯 넣기
```
tools.pot.pour(ingredients.driedShiitakeMushrooms);
```

말린 다시마 넣기
```
tools.pot.pour(ingredients.driedKelp);
```

황설탕 넣기
```
tools.pot.pour(ingredients.brownSugar);
```

가쓰오부시 넣기
```
tools.pot.pour(ingredients.katsuobushi);
```

간보고 싱거우면 혼쯔유 더 넣기
```
if(me.feel(bland)){
    tools.pot.pour(ingredients.tzuyu);
}
```

불 끄기
```
cooking.turnOffFire();
```

체에 걸러 다시마와 가쓰오부시 제거
```
tools.sieve.strain();
```

#### 소고기 굽기

불 켜기
```
cooking.turnOnFire();
```

우삼겹 넣기
```
tools.pan.pour(ingredients.shortPlate);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

불 끄기
```
cooking.turnOffFire();
```

#### 면 삶기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

우동면 넣기
```
tools.pot.pour(ingredients.udonNoodles);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

우동면 넣기
```
tools.bowl.pour(ingredients.udonNoodles);
```

우동국물 넣기
```
tools.bowl.pour(ingredients.udonSoup);
```

우삼겹 넣기
```
tools.bowl.pour(ingredients.roastedShortPlate);
```

대파 넣기
```
tools.bowl.pour(ingredients.greenOnion);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

싱거우신가요? 우동국물은 짭게 만드셔야합니다. 우삼겹에 간을 하지 않았기 때문이죠. 잘 드셨다면 정리해주세요.

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
