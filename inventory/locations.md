
# LOCATIONS

## TABEL

|#| field_name | type | p_key | n_null | link_table |
|-|---|---|:---:|:---:|---|
|1| block_id     | STRING |*|*| [blockchain](/system/blockchain.md) |
|2| date_created | DATE   | | |            | 
|3| company_id | STRING   |*|*| company    | 
|4| location_id | STRING   |* |* |  | 
|5| location_name | STRING   | | |  | 
|6| location_inactive | BOOLEAN   | | |  | 
|7| location_type | INTEGER   | | |  | 


## METODE

* [create](#create)
* [read_paging](#read_paging)
* [read_one](#read_one)
* [update](#update)
* [delete](#delete)
* [search](#search)
* [export](#export)

## <a name="create"> CREATE

### Address
* https://api.rangkaidata.com/locations/create

### JSON Request
```JSON
{
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "location_id": "<STRING>",
  "location_name": "<STRING>",
  "location_inactive": "<BOOLEAN>",
  "location_type": "<INTEGER>"
}
```
### JSON Response

```JSON
{
  ""
}
```
## <a name="read_paging">READ_PAGING

### Address
* https://api.rangkaidata.com/locations/read_paging

### JSON Request
```JSON
{
  "login_id": "<STRING>",
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "page": "<INTEGER>",
  "limit": "<INTEGER>",
  "filter": "<OBJECT>"
}
```

### JSON Response

## <a name="read_one">READ_ONE

### Address
* https://api.rangkaidata.com/locations/read_one

### JSON Request
```JSON
{
  "login_id": "<STRING>",
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "location_id": "<STRING>"
}
```

### JSON Response

## <a name="update">UPDATE

### Address
* https://api.rangkaidata.com/locations/update

### JSON Request
```JSON
{
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "location_id": "<STRING>",
  "location_name": "<STRING>",
  "location_inactive": "<BOOLEAN>",
  "location_type": "<INTEGER>"
}
```

### JSON Response

## <a name="delete">DELETE

### Address
* https://api.rangkaidata.com/locations/delete

### JSON Request
```JSON
{
  "login_id": "<STRING>",
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "location_id": "<STRING>"
}
```

### JSON Response

## <a name="search">SEARCH

### Address
* https://api.rangkaidata.com/locations/search

### JSON Request
```JSON
{
  "login_id": "<STRING>",
  "company_id": "<STRING>",
  "invite_id": "<STRING>",
  "search": "<STRING>"
}
```

### JSON Response

## <a name="export">EXPORT

### Address
* https://api.rangkaidata.com/locations/export

### JSON Request
```JSON
{
  "login_id": "<STRING>",
  "company_id": "<STRING>",
  "invite_id": "<STRING>"
}
```

### JSON Response

