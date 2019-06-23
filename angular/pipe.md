# Pipe

Changing the data itself can have a side effect. Therefore, if you want to change the format displayed on the screen, use a pipe.

## Create Pipe

```bash
$ng new <name> -t -s -S

$ng cd <name>

$ng generate <name> [option]
```

## title

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

## How to Use

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



