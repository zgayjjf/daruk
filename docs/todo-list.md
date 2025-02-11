# Feature todo list

We want be support features before v1.0.0 version's todo list:

- request:

  - [ ] @required({methodName:key})
  - [ ] @validate(method,key,validFunc])
  - [ ] @useAuth(middleware)
  - [ ] @security(type,username,password)

- response:

  - [x] @header(key|fields, ?value)
  - [x] @type(type:string)
  - [x] @redirect(path:string)
  - [ ] @cache

- arguments:

  - [ ] @param(key:string)
  - [ ] @body(key:string)
  - [ ] @query(key:string)
  - [ ] @headers(key?:string)

- Class:

  - [ ] @controller(path:string)
  - [ ] @timer(cronTime:string)
  - [ ] @inject(LibName:string)
  - [ ] @provide(LibName)
  - [ ] @ctx(routerPath)

- controllerClass:

  - [ ] @local
  - [x] @prefix(path:string)

- utils:

  - [ ] @decorator
  - [ ] @globalSetting
