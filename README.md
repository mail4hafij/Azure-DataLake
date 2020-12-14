# Azure-DataLake

## TODO

<img src="multi-protocol-access.jpg" />


## Blob storage vs ADL Gen2 Storage


|               | Blob Storage      | ADL Gen2 Storage |
| ------------- | ----------------- | ---------------- |
| Access tiers  | yes               |  yes             |
| Top level     | Container         | Container        |
| Lower level   | Virtual directory | Directory        |
| Container     | Blob              | File             |




|                    | Blob Storage      | ADL Gen2 Storage |
| ------------------ | ----------------- | ---------------- |
| Soft delete        | Yes               | No               |
| Snapshots          | Yes               | No               |
| Immutable storage  | Yes               | No               |
| Blobfuse           | Yes               | No               |



|                                 | Blob Storage      | ADL Gen2 Storage |
| ------------------------------- | ----------------- | ---------------- |
| Access keys                     | Yes               | Yes              |
| Shared Access Signature (SAS)   | Yes               | Yes              |
| RBAC                            | Yes               | Yes              |
| Access Control Lists            | No                | Yes              |

