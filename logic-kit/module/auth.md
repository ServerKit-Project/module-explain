---
description: 2차 인증 모듈
---

# Auth

### signUp2faSave

#### Parameters

* phoneNumber: string
* verificationCode: string
* TTL: number

#### Return

* result: number

***

### validateMFASession

#### Parameters

* userGroupId: string
* verificationCode: string
* sessionId: string

#### Return

* result: object

***

### signUp2faCheck

#### Parameters

* verificationCode: string
* phoneNumber: string

#### Return

* result: boolean

***

### createMFASession

#### Parameters

* userGroupId: string
* verificationCode: string
* userId: string
* TTL: number

#### Return

* result: object

***
