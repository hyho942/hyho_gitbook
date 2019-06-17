# How to Use Angular

Angular CLI requires Node.js 6.9.0, NPM 3.0.0 or higher.

* Node.js install =&gt;
* npm install =&gt;

#### Angular Installation

```bash
$npm install -g @angular/cli
```



> Delete existing version

```bash
$npm uninstall -g @angular/cli
```

* Delete Angular CLI

```bash
$npm cache verify
```

* Verify Cache Matching

```bash
$npm install -g angular/cli@latest
```

* Install Angular CLI



> Option

```bash
$ng version
```

```bash
$ng help
```



#### Project Create

```bash
$ng new <project Name>
```

* A new project is created and the scaffolding is created.

```bash
$cd <project Name>
```

```bash
$ng serve
$ng serve -o
$ng serve --open
```

* Project lunch at localhost environment, -o , --open is automatically open browser. 

```bash
$ng serve --port 4500
```

* Change the server port





* 8.     서버가 구동할 때, \(&lt;project-name&gt;/src/app/component.ts\)를 수정하고 저장하면, LiveReload 기능이 자동적으로 페이지를 리로드 해준다.

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

