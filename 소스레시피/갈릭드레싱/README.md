# 갈릭드레싱 알고리즘

갈릭드레싱 알고리즘에 대해 알아 봅시다.

## Getting Started

샐러드에 뿌려먹기 좋은 갈릭드레싱 만들어보겠습니다.
 
### Prerequisites

갈릭드레싱를 위한 기본적인 준비물입니다.

```
먀요네즈
```
```
간마늘
```
```
황설탕
```
```
사이다
```

##### 조리도구

```
그릇
```
```
숟가락
```
```
전자레인지
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

정리는 필수입니다.
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

마요네즈 넣기
```
tools.bowl.pour(ingredients.mayonnaise);
```

간마늘 넣기
```
tools.bowl.pour(ingredients.groundGalric);
```

사이다 넣기
```
tools.bowl.pour(ingredients.sprite);
```

황설탕 넣기
```
tools.bowl.pour(ingredients.brownSugar);
```

섞기
``` 
tools.bowl.mix();
```

전자레인지 15초 돌리기
``` 
tools.microwave.heat(15, "sec");
```

냉장보관
``` 
Keep it refrigerated.
```
### Cleaning

마늘의 알싸한 맛을 빼기위해선 냉장숙성하시면됩니다. 맛있게 드시고 정리 잘 해주세요.

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
