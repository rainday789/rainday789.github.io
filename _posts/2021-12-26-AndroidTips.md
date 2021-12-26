---
layout: single
title:  "Android 개발 관련 trouble shooting tips"
published: true
---

✔️"error: style attribute 'attr/colorPrimary' not found" 에러

build.gradle(app) 다음과 같은 코드 추가

```xml
implementation ‘com.android.support:appcompat-v7:28.0.0’
```

OR

```xml
implementation 'androidx.appcompat:appcompat:1.2.0'
```

OR





