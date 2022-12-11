# 콩나물국밥 알고리즘
오늘은 콩나물국밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

전날 술을 너무 많이 먹었더니 머리가 띵하네요. 오늘을 콩나물 국밥으로 해장을 하려합니다.

### Prerequisites

쿵나물국밥 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
숟가락
```
```
육수팩
```
```
콩나물
```
```
다진마늘
```
```
청양고추
```
```
국간장
```
```
후추
```
```
쌀
```
```
참지액젓(optional)
```
```
고춧가루(optional)
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

설거지를 안했더니 주방이 많이 더럽더라구요. 먼저 요리하기위해 쌓아둔 설거지 더미들을 처리해줍니다. 
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

육수팩 넣기
```
tools.pot.pour(ingredients.stockPack);
```

5분뒤 건져내기
```
tool.pot.remove(ingredients.stockPack, 5, "min");
```

간마늘 넣기
```
tools.pot.pour(ingredients.crushedGarlic);
```

파 넣기
```
tools.pot.pour(ingredients.greenOnion);
```

콩나물 넣기
```
tools.pot.pour(ingredients.beanSprouts);
```

국간장 넣기
```
tools.pot.pour(ingredients.soupSoySauce);
```

참치액젓 넣기(optional)
```
tools.pot.pour(ingredients.tunaSauce);
```

청양고추 넣기
```
tools.pot.pour(ingredients.redPepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Eating

맛있게 먹기
```
if(me.wantSpicy){
    tools.bowl.pour(ingredients.redPepperPowder);
}

tools.bowl.pour(ingredients.pepper);

me.eat();
```

### Cleaning

속들은 잘 푸셨나요? 귀찮더라도 먹은 음식은 바로 치우는것이 좋습니다.
맛있게 드셨다면 사용하신 모든 도구들을 청소하고 정리하시면 됩니다.

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
