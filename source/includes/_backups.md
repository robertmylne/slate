# Backups

## All backups

> Definition

```shell
GET /websites/{WHM_ID}/backups
```

> Example Request

```json
{}
```


> Example Response

```json
{}
```

This endpoint returns a list of all website backups.

### HTTP Request

`GET /websites/{WHM_ID}/backups`

### URL Parameters

Parameter | Description
--------- | -----------
WHM_ID | The username of the cPanel account

## Create a backup

> Definition

```shell
POST /websites/{WHM_ID}/backups
```

> Example Request

```json
{}
```


> Example Response

```json
{}
```

This endpoint creates a website backup.

### HTTP Request

`POST /websites/{WHM_ID}/backups`

### URL Parameters

Parameter | Description
--------- | -----------
WHM_ID | The username of the cPanel account

## Restore a backup

> Definition

```shell
POST /websites/{WHM_ID}/backups/{BACKUP_ID}
```

> Example Request

```json
{}
```


> Example Response

```json
{}
```

This endpoint restores a website backup.

### HTTP Request

`POST /websites/{WHM_ID}/backups/{BACKUP_ID}`

### URL Parameters

Parameter | Description
--------- | -----------
WHM_ID | The username of the cPanel account
BACKUP_ID | The string name of the backup

## Delete a backup

> Definition

```shell
DELETE /websites/{WHM_ID}/backups/{BACKUP_ID}
```

> Example Request

```json
{}
```


> Example Response

```json
{}
```

This endpoint deletes a website backup.

### HTTP Request

`DELETE /websites/{WHM_ID}/backups/{BACKUP_ID}`

### URL Parameters

Parameter | Description
--------- | -----------
WHM_ID | The username of the cPanel account
BACKUP_ID | The string name of the backup