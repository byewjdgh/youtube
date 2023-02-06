# 고추잡채 알고리즘

오늘은 고추잡채 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

파프리카가 남아있습니다. 고추잡채 만들어보겠습니다.
 
### Prerequisites

고추잡채 요리를 위한 기본적인 준비물입니다.

#### 고추잡채 식재료

```
돼지 잡채용 등심
```
```
식용유
```
```
고추기름
```
```
파프리카
```
```
양파
```
```
청양고추
```
```
표고버섯
```
```
소금
```
```
후추
```
```
고춧가루
```
```
진간장
```
```
굴소스
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

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

고추잡채는 재료준비가 많습니다. 정리해주세요.
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

#### 고추잡채 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

등심 넣기
```
tools.pan.pour(ingredients.porkSirloin);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

표고버섯 넣기
```
tools.pan.pour(ingredients.shiitakeMushroom);
```

파프리카 넣기
```
tools.pan.pour(ingredients.paprika);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangRedPepper);
```

굴소스 넣기
```
tools.pan.pour(ingredients.oysterSauce);
```

진간장 넣기
```
tools.pan.pour(ingredients.soySauce);
```

고추기름 넣기
```
tools.pan.pour(ingredients.redPepperOil);
```

고춧가루 넣기
```
tools.pan.pour(ingredients.redPepperPowder);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

고추잡채 담기
```
tools.dish.plating(pepperSteak);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨습니까? 파프리카를 넣으니 달더라구요. 그래서 고춧가루를 추가하였습니다. 다음엔 피망을 넣어 해봐야겠습니다. 이제 정리해주세요.

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
