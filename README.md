# mongodb generic id

A generic form of mongodb id

```typescrit
import {ObjectId} from 'mongodb'
import {Id} from 'mongodb-generic-id'

const nongeneric: ObjectId = new ObjectId()
const generic: Id<MyModel> = new ObjectId()
```
