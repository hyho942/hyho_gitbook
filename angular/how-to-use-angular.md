# How to Use Angular

Angular CLI requires Node.js 6.9.0, NPM 3.0.0 or higher.

* Node.js install =&gt;
* npm install =&gt;

## Angular Installation

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

## Project Create

```bash
$ng new <project Name> [option]
$ng n <project Name> [option]
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

## Component Create Command

| Create Component | Commend | Abbreviation |
| :--- | :--- | :--- |
| Component | ng generate component &lt;name&gt; \[option\] | ng g c &lt;name&gt; \[option\] |
| Directive | ng generate directive &lt;name&gt; \[option\] | ng g d &lt;name&gt; \[option\] |
| Pipe | ng generate pipe &lt;name&gt; \[option\] | ng g p &lt;name&gt; \[option\] |
| Service | ng generate service &lt;name&gt; \[option\] | ng g s &lt;name&gt; \[option\] |
| Module | ng generate module &lt;name&gt; \[option\] | ng g m &lt;name&gt; \[option\] |
| Guard | ng generate guard &lt;name&gt; \[option\] | ng g g &lt;name&gt; \[option\] |
| Class | ng generate class &lt;name&gt; \[option\] | ng g cl &lt;name&gt; \[option\] |
| Interface | ng generate interface &lt;name&gt; &lt;type&gt;  \[option\] | ng g i &lt;name&gt; &lt;type&gt;  \[option\] |
| Enum | ng generate enum &lt;name&gt; \[option\] | ng g e enum-name &lt;name&gt; \[option\] |

### \[Option\]

     \*-s\* \( --inlineStyle = true \| false \)

    : 인라인 스타일로 생성

    \(When true, includes styles inline in the component TS file.\)

     \*-t\* \( --inlineTemplate = true \| false \)

    : 인라인 템플릿으로 생성

    \(When true, includes template inline in the component TS file.\)

     \*-S\* \( --skipTests = true \| false \)

    : 대문자 S, 테스트 파일을 생성하지 않는다.

    \(When true, does not generate "spec.ts" test files for the new project.\)

     \*-g\* \( --skipGit = true \| false \)

    : 깃 레포지토리를 초기화 하지 않음

    \(When true, does not initialize a git repository.\)

## Component Naming Convention

Angular CLI using kebab-case

projectComponent =&gt; project-component

ProjectComponent =&gt; project-component



## Generated Component

./src/app

&lt;Project Name&gt;.component.html

&lt;Project Name&gt;.component.css

&lt;Project Name&gt;.component.ts

&lt;Project Name&gt;.component.spec.ts 

