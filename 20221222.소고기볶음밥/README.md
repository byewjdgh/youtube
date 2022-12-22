# 소고기 볶음밥 알고리즘

오늘은 소고기 볶음밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

남은 국거리용 소고기를 이용해 소고기 볶음밥과 누룽지 만들어보겠습니다.
 
### Prerequisites

소고기 볶음밥 요리를 위한 기본적인 준비물입니다.

#### 식재료

```
물
```
```
누룽지
```
```
식용유
```
```
쪽파
```
```
소고기 다짐육
```
```
간마늘
```
```
진간장
```
```
밥
```
```
후추
```
```
참기름
```
```
통깨(optional)
```
##### 조리도구

```
냄비
```
```
칼
```
```
스패츌러
```
```
접시
```
#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

이번 음식은 대충 끼니를 해결하기 위해 하는 음식입니다. 그래도 정리를 필수입니다.
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

#### 소고기 볶음밥 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

쪽파 넣기
```
tools.pot.pour(ingredients.greenOnion);
```

소고기 다짐육 넣기
```
tools.pot.pour(ingredients.beefGroundMeat);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

진간장 넣기
```
tools.pot.pour(ingredients.soySauce);
```

밥 넣기
```
tools.pot.pour(ingredients.boiledRice);
```

후추 넣기
```
tools.pot.pour(ingredients.pepper);
```

참기름 넣기
```
tools.pot.pour(ingredients.sesameOil);
```

간보고 싱거우면 간장 더 넣기
```
if(!me.feel(salty)){
    tools.pot.pour(ingredients.soySauce);
}
```

불 끄기
```
cooking.turnOffFire();
```
#### 누룽지 만들기

물 넣기
```
tools.pot2.pour(ingredients.water);
```

불 켜기
```
cooking.turnOnFire();
```

누룽지 넣기
```
tools.pot2.pour(ingredients.nurungji);
```

불 끄기
```
cooking.turnOffFire();
```

### Eating

통깨 넣기(optional)
```
tools.bowl.pour(ingredients.sesame);
```

맛있게 먹기
```
me.eat();
```

### Cleaning

간단한 요리 였습니다. 정리는 잊지마세요.

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
