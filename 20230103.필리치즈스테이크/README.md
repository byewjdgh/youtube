# 필리치즈스테이크 알고리즘

오늘은 필리치즈스테이크 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

남은 소불고기로 필리치즈스테이크 만들어보겠습니다.
 
### Prerequisites

필리치즈스테이크 요리를 위한 기본적인 준비물입니다.

#### 필리치즈스테이크 식재료

```
소불고기
```
```
양파
```
```
모닝빵
```
```
버터
```
```
밀가루
```
```
우유
```
```
체다치즈
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
접시
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

간단한 요리지만 정리는 해주세요.
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

#### 치즈 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

버터 넣기
```
tools.pot.pour(ingredients.butter);
```

밀가루 넣기
```
tools.pot.pour(ingredients.flour);
```

체다치즈 넣기
```
tools.pot.pour(ingredients.cheddarCheese);
```

우유 넣기
```
tools.pot.pour(ingredients.milk);
```

불 끄기
```
cooking.turnOffFire();
```

#### 소불고기 굽기

불 켜기
```
cooking.turnOnFire();
```

소불고기 넣기
```
tools.pan.pour(ingredients.bulgogi);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

빵 파기
```
ingredients.dinnerRoll.dig();
```

소불고기 넣기
```
ingredients.dinnerRoll.put(bulgogi);
```

치즈소스 넣기
```
ingredients.dinnerRoll.put(cheeseSauce);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

소불고기와 모닝빵을 이용해 만들어보았습니다. 실제 필리치즈스테이크는 호기롤을 사용하지만 주변에 없어서 모닝빵으로했습니다. 잘 정리해주세요.

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
