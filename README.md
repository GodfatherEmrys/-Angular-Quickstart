# AngularQuickStart

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Node version Manager

 - n
 - nvm
 - nvs

## NVM

```
nvm alias default 8.9.0
```

## VSCODE

-code shell path
code [DIRPATH]


shadow DOM : 보이지 않는 돔으로 따로 처리한다 실제 돔은 아님 과거에는 모든 돔을 알고 있었지만, 커스텀 엘리먼트단위로 제어.. 인풋 아웃풋을 쉐도우 돔 트리 안에서 동작함... 오......

웹콤포: 풀리머? 폴리머??

test - next week
server side render - last week ( angular universal )

ng generate component  sample1 --inline-template --inline-style
==
ng g c -it -s

## COMPONENT

콤포넌트에 뭔가를 달아서 보내주는 것 데이터를 주고 받고 하기
똑똑콤 : 데이터를 다루는 콤 스마트 컴퍼넌트
바보콤 : 데이터만 중재 프레젠테이션 컴퍼넌트

## ngModel

FORMSMODULE
FormsModule을 임포트해서 넣어줘야함
import { FormsModule } from '@angular/forms';
  imports: [
    FormsModule
  ],

### ZEST? React 테스트 도구

### JASMIN KARMA angular 테스트 도구

### DI

자바스크립트에서는 DI개념이 없엇는데 TS에 오면서 생겼다
Dependency Injection
InversifyJS

### 변경 감시전략


### HOC를 사용하고 상속형식은 잘 하지 않는다..

<A B=B></A>
컴퍼지션 방식으로..

async await & observable

### 서비스

공유할 필요가 있을 때는 서비스를 사용하기도 하고.. 각자에 넣어서 사용하기도 한다...

### 서비스가 뭔데?

컴포넌트 뷰를 위한 모델..

서비스 : 컴포넌트는 공통적인 로직이나 함수들의 모임, 별도로 빼놓는 기능 - DI가 필요함

A 콤포넌트에 S 서비스를 주입한다는 의미라고 볼 수 있다
객체를 미리 만들어서 주입해서 사용하는 방식

control 인벌젼? 타 컴포넌트에서 사용할 엔지를 주입 .. ? 제어의 역전
dependency injector 

설정하는 방식은 같으나, 설정하는 위치가 다름 
