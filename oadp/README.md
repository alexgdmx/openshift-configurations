## OADP (OpenShift API for Data Protection) operator sets up and installs Data Protection Applications on the OpenShift platform.


```bash
$ oc create secret generic cloud-credentials --namespace openshift-adp --from-file cloud=
```

## Tool to generate minio-keyes

###  Requirements

- go Toolset

```bash
$ go install github.com/iwittkau/minio-keygen@latest
```

Run
```
[alex@bastion oadp]$ minio-keygen
MINIO_ROOT_USER=HZMURK8VBZIWVXF2_PBEUUT3
MINIO_ROOT_PASSWORD=GyL5eHQ-TslPj8833xkUQtK77J2H8GNycohNuFSUy4Es2X6O
```
