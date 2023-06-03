# Usage
## update schema
```bash
export SHOP_STORE="<your store name>"
export SHOP_TOKEN="<your admin app token>"
export SHOPIFY_API_VERSION="<api version you wish to use>"

sh path/to/update_schema.sh
```
### update operations
You must define your own operations in a file `shopify_operations.gql`. Then
```bash
sh path/to/update_operations.sh
```