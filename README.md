# Mongo ObjectId Class Validator
This package validates Mongo ObjectId.

## How to install
```bash
npm i -S class-validator-mongo-object-id
```

## How to use
Here is an example along with commonly used `IsString` from [`class-validator`](https://github.com/typestack/class-validator) package.

```ts
import { IsString } from 'class-validator';
import { IsObjectId } from 'class-validator-mongo-object-id';

class UserDTO {
    @IsObjectId()
    id: string;

    @IsString()
    name: string;
}
```
