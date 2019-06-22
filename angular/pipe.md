# Pipe

Changing the data itself can have a side effect. Therefore, if you want to change the format displayed on the screen, use a pipe.

| Pipe | Mean |
| :--- | :--- |
| **date : ' '** | Date format conversion |
| **json** | JSON format conversion |
| **uppercase** | Uppercase conversion |
| **lowercase** | Lowercase conversion |
| **currency : 'USD' : 'symbol' : '1.1-2'** //=&gt; $5.99 | Currency format conversion |
| **percent : ' '** | Percent format conversion |
| **decimal** | Decimal format conversion |
| **slice : '2'** //=&gt; cut second character and return | String extraction |
| **async** | Asynchronism object extraction |



사용법

```typescript
{{ value | pipeName }}
```

// Pipe option

```typescript
{{ value | pipeName : ‘display option’}}
```

// Pipe chaining

```typescript
{{ value | pipeName1 | pipeName2 }}
```

파이프 생성

$ ng new &lt;name&gt; -t -s -S

$ ng cd &lt;name&gt;

$ ng generate &lt;name&gt; \[option\]

