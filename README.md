## How To Start

```console
bundle exec jekyll s
```

## H2 Tag

### H3 Tag

#### H4 Tag

1. 안녕
2. 안녕

- 안녕
    - 안녕

```sql
select employee_id, concat(first_name, ' ',last_name) as name, salary, hire_date, job_id, manager_id
from employees
where employee_id;
```

```js
const youna = {age: 29}
```

```ts
console.log("안녕")
```

```yaml
services:
  mysqlhr:
    image: mysql:latest
    environment:
      MYSQL_ROOT_PASSWORD: 1234
    ports:
      # 외부에 노출되는 포트 / 내부 포트
      - "13310:3306"
    networks:
      - youna

networks:
  youna:
    driver: bridge
```