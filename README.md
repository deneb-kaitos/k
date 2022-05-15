# k

**k** stands for **k**aufman.

## layout

```pre
/sources
  |
  +- back-end
  |    |
  |    +- libs
  |    |
  |    +- domains
  |          |
  |          +- api
  |          |
  |          +- token
  |          |
  |          +- user-authentication
  |          |
  |          +- user-registration
  |
  +- front-end
  |
  +- common
  |    |
  |    +- libs
```

### /sources/back-end

For details please see the [BACK-END.md](sources/back-end/BACK-END.md) file.

```bash
./libs # every single library lives here
```

```bash
./domains # every business domain lives here. For now there are api, token, user-{registration, authentication}
```

### /sources/front-end

here lives the main web application.

For details please see the [FRONT-END.md](sources/front-end/FRONT-END.md) file.

### /sources/common

```bash
./libs # every single library that is used both in the back-end and in the front-end must live here
```

For details please see the [COMMON.md](sources/common/COMMON.md) file.
