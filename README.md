# Mongo ObjectId Class Validator
This package validates Mongo ObjectId.

## How to install
```bash
npm i -S mongo-object-id-class-validator
```

## How to use
Here is an example along with commonly used `IsString` from [`class-validator`](https://github.com/typestack/class-validator) package.

```ts
import { IsString } from 'class-validator';
import { IsObjectId } from 'mongo-object-id-class-validator';

class UserDTO {
    @IsObjectId()
    id: string;

    @IsString()
    name: string;
}
```
