Initialization within README.md

## Install guide

Create secrets manually, e.g. `oc create secret generic mssql --from-literal=SA_PASSWORD="Goodp@ss"`

For some reasons some passwords failed to work correctly. This one is fine for user sa

Example of sql-cli command to access: `mssql -o <exposed_port> -u sa -s <node_ip> -p <your_pw>`

## Links

During installation I reffered to https://joeydantoni.com/2018/04/05/getting-started-with-sql-sql-server-and-kubernetes-part-ii/
