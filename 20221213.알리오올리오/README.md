# 알리오올리오 알고리즘
오늘은 알리오올리오 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started
곧 연말도 다가오니 연인 및 가족, 지인들과 함께 집에서 만들어보세요.
 
### Prerequisites

알리오올리오 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
스파게티니
```
```
엑스트라버진오일 또는 식용유
```
```
숟가락
```
```
포크
```
```
치킨스톡
```
```
마늘
```
```
페퍼론치노
```
```
소금
```
```
후추
```
```
파르지아노 레지아노 치즈(optional)
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

요리의 기본은 정리부터 시작입니다. 씽크대가 더럽다던가 준비가 덜된 느낌이라면 정리부터 해주세요.
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

모든 변수가 초기화 되었으니 요리를 시작하시면됩니다.

냄비에 물 붓기
```
tools.pot.pour(ingredients.water);
```

불 켜기
```
cooking.turnOnFire();
```

물이 끓을때 까지 기다리기
```
while(!tools.pot.isBoiled){
    me.wait();
}
```

치킨스톡 넣기
```
tools.pot.pour(ingredients.chickenStock);
```

스파게티니 넣기
```
tools.pot.pour(ingredients.spaghettini);
```

면이 익을때 까지 기다리기
```
while(!ingredients.spaghettini.isCooked){
    me.wait();
}
```
 
불 켜기
```
cooking.turnOnFire();
```

오일 넣기
```
tools.pot2.pour(ingredients.oil);

```

마늘 및 페퍼론치노 넣기
```
tools.pot2.pour(ingredients.galric, ingredients.peperoncino);

```

화구 변경
```
cooking.changeFire();
```

면 넣기
```
tools.pot2.pour(ingredients.spaghettini);
```

면수 넣기
```
tools.pot2.pour(ingredients.stockSoup);
```

소금 넣기(optional)
```
if(!me.feel(salty)){
    tools.pot2.pour(ingredients.salt);
}
```

불 끄기
```
cooking.turnOffFire();
```

면을 먹고 간과 익힘 정도를 직접 확인
```
me.check(ingredients.spaghettini);
```

후추 넣기
```
tools.bowl.pour(ingredients.pepper);

```

파르지아노 레지아노 치즈 넣기(optional)
```
tools.bowl.pour(ingredients.cheeze);

```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛은 있으신가요? 면이 덜 익었을수도 있고 짭다고 느낄수도 있고 맛이 없을수도 있습니다.<br>
한번에 맛있을 수는 없죠. 시행착오끝에 결국엔 맛있게 만드실수 있을거라 믿습니다.
이제 정리하시고 남은 22년 마무리 잘하세요.

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
