# Ansible role - `k8s_volsnap`

Manage Volume Snapshot CRDs and Volume Snapshot Controller on Kubernetes clusters.

## Tags

| Tag      | Description                            |
|----------|----------------------------------------|
| `apply`  | Deploy Volume Snapshot CRDs Controller |
| `delete` | Delete Volume Snapshot CRDs Controller |
 
## Variables

| Variable              | Type     | Required | Defaut        | Description                                 |
|-----------------------|----------|----------|---------------|---------------------------------------------|
| `k8s_volsnap_version` | `string` | No       | `release-2.1` | Volume Snapshot CRDs and Controller version |


## Tasks sequence

```text
--------------------------- tags: apply, delete --
main.yml
```
