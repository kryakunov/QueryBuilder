# Usage
```php 
require_once('QueryBuilder.php');
$QueryBuilder = new QueryBuilder(pdo $pdo);
```

### Get all columns
```php 
$QueryBuilder->getAll($table);
```

### Get one column
```php 
$QueryBuilder->getOne($table, $id);
```

### Create column
```php 
$QueryBuilder->create($table, $data);
```

### Update column
```php 
$QueryBuilder->update($table, $id);
```

### Delete column
```php 
$QueryBuilder->delete($table, $id);
```
