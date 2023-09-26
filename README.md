# go-libraryofcongress-database-docstore

## Important

Work in progress. There are still bugs.

## Example

```
$> ./bin/query -database-uri 'awsdynamodb://{TABLE_NAME}?region={REGION}&credentials={CREDENTIALS}&partition-key=Id' 'Gurdus, Luba, 1914-'
lcnaf:n87103971 Gurdus, Luba, 1914-
```

## See also

* https://github.com/sfomuseum/go-libraryofcongress
* https://github.com/sfomuseum/go-libraryofcongress-database
* https://godoc.org/gocloud.dev/docstore