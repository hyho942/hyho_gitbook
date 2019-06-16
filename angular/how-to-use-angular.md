# How to Use Angular

Angular CLI requires Node.js 6.9.0, NPM 3.0.0 or higher.

* Node.js install =&gt;
* npm install =&gt;

#### Angular Installation

1.     npm install -g @angular/cli

a.     기존 버전 삭제

i.     Npm uninstall -g @angular/cli // 삭제

ii.     Npm cache verify // 캐시 정합성 확인

iii.     Npm install -g angular/cli@latest // 설치

2.     Ng version // 버전 확인

3.     Ng help

4.     Ng new &lt;project-name&gt;

a.     새로운 프로젝트가 생성되고 스캐폴딩이 작성된다.

5.     Cd &lt;project-name&gt;

6.     Ng serve // 프로젝트 실행- localhost 접속 가능

a.     Ng serve –open // 자동으로 서버를 실행 해준다.

7.     Ng serve –port 4500 // 서버 포트를 바꿀수 있다.

8.     서버가 구동할 때, \(&lt;project-name&gt;/src/app/component.ts\)를 수정하고 저장하면, LiveReload 기능이 자동적으로 페이지를 리로드 해준다.

#### Component Create Command

| Create Component | Commend | Abbreviation | f |
| :--- | :--- | :--- | :--- |
| Component | ng generate component \(component-name\) | ng g c \(component-name\) | UI Create |
| Directive | ng generate directive directive-name | ng g d directive-name |  |
| Pipe | ng generate pipe pipe-name | ng g p pipe-name |  |
| Service | ng generate service service-name | ng g s service-name |  |
| Module | ng generate module module-name | ng g m module-name |  |
| Guard | ng generate guard guard-name | ng g g guard-name |  |
| Class | ng generate class class-name | ng g cl class-name |  |
| Interface | ng generate interface interface-name | ng g i interface-name |  |
| Enum | ng generate enum enum-name | ng g e enum-name |  |

