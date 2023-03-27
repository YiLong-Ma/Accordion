# environmental variable

1. Create a file at the root
```
.env
```

2. inside the .env file add the text:
- you must use `NEXT_PUBLIC` or else this will not work

```
NEXT_PUBLIC_TITLE = " Digital Design and Development Diploma"
```

3. on the page, in between the export and return write the variable:
```
var title = process.env.NEXT_PUBLIC_TITLE
```

4. then in between the main write:
```
{title}
```

5. make sure the `.gitignore` file has the `.env` inside
- you want to prevent this secret title to be shown

## BCIT Data from Digital Design and Development Diploma 
[Digital Design and Development Diploma ](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/#courses)