# Contents of 'lib' directory
* All utilities used by React components or API routes
* Data fetching, library initialization, Prisma setup, database access, a fetcher for SWR, the easy-peasy store
* Anything that could be reused anywhere but it’s not a component
* These can be included like this:

```
import comp from components/Common/comp
import x from lib/x
```

* by setting up jsconfig.json

```
{
  "compilerOptions": {
    "baseUrl": "."
  }
}
```