# Smiley cam

android/ios app that take a picture when you smiling.
노마드코더를 보고 따라 만든 앱입니다.

## 완성 모습

![smiley-cam](https://drive.google.com/uc?id=1KkCnwsQzowvUH-jSTrvCSOYV9zBO6FlX)  
버튼을 누르면 카메라가 전후방 교체 가능  

## expo 권한 허용

```js
import * as Permissions from "expo-permissions";

const { status } = await Permissions.askAsync(권한);
// 권한은 "granted"가 되면 승인된 것임
```

각 기능마다 권한이 허용되면 사용 가능함 