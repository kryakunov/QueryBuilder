# Usage
require_once('QueryBuilder.php');
$QueryBuilder = new QueryBuilder(pdo $pdo);

# Get all columns
$QueryBuilder->getAll($table);

# Get one column
$QueryBuilder->getOne($table, $id);

# Create column
$QueryBuilder->create($table, $data);

# Update column
$QueryBuilder->create($table, $id);


# Delete column
$QueryBuilder->create($table, $id);
