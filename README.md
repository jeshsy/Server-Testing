# **Server Testing Commits**
* Get a Commit
* Put a Commit
* Post a Commit
* Delete a Commit


## Get a Commit
`GET /localhost:8080/food/`

### Response
`Status: 200 OK`
```
{
  "name": "pizza"
}
```

## Post a Commit
`POST /localhost:8080/food/`

### Parameters
**Name** |	**Type**	|  **Description**
--- | --- | ---
`food` | `string` |  **Required.** The commit message

### Example Input

```
{
  "name": "steak",
}
```

### Response
```
Status: 201 Created
```

## Put a Commit
`PUT /localhost:8080/food/`

### Response
`Status: 200 OK`
```
{
  "name": "pizza"
}
```

## Delete a Commit
`DELETE /localhost:8080/food/`

### Response
`Status: 200 OK`
```
{
  "name": "pizza"
}
```
