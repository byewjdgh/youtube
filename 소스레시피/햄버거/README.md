# 햄버거 소스 알고리즘

햄버거 소스 알고리즘에 대해 알아 봅시다.

## Getting Started

햄버거 소스 입니다.
 
### Prerequisites

햄버거 소스를 위한 기본적인 준비물입니다.

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
믹싱볼
```
```
스패츌러
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
