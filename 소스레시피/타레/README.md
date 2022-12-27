# 타레 소스 알고리즘

타레 소스 알고리즘에 대해 알아 봅시다.

## Getting Started

덮밥에 쓰이는 타레 소스 입니다.
 
### Prerequisites

타레 소스를 위한 기본적인 준비물입니다.

```
혼쯔유
```
```
마늘
```
```
가쓰오부시
```
```
물
```
```
황설탕
```

##### 조리도구

```
냄비
```
```
스패츌러
```
```
거름망
```
```
종지
```
```
숟가락
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

#### 타레 베이스 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

혼쯔유 넣기
```
tools.pan.pour(ingredients.tsuyu);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

가쓰오부시 넣기
```
tools.pan.pour(ingredients.katsuobushi);
```

불 끄기
```
cooking.turnOffFire();
```

#### 타레 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

황설탈 넣기
```
tools.pan2.pour(ingredients.brownSugar);
```

물 넣기
```
tools.pan2.pour(ingredients.water);
```

캐러멜화 될때까지 기다리기
```
while(!ingredients.brownSugar.isCaramelized()){
    me.wating();
}
```

베이스 소스 넣기
```
tools.pan2.pour(ingredients.baseSauce);
```

졸이기
```
tools.pan2.boilDown();
```

불 끄기
```
cooking.turnOffFire();
```

거름망을 이용해 소스 걸러내기
```
tools.dish.pourWithFilter(ingredients.tareSauce);
```

### Cleaning

맛있게 드시고 정리 잘 해주세요.

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
