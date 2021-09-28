# apic-demo
  
  Curl command to get an API Token
```
curl -v -u client_id:client_secret -k -X POST -d "grant_type=password&scope=scope_name&username=user_name&password=password" "https://gw_api/org_name/catalog_name/oauth/oauth2/token"
```
For example:
```
curl -v -u af1ba97fd3c933da7973a41517d9170b:8aa495753c6b3d971f4ed8fd205d4f8d -k -X POST -d "grant_type=password&scope=all_scope&username=admin&password=admin" "https://apis-minimum-gw-gateway-cp4i.ibmcloud-roks-jcyk96sg-4b4a324f027aea19c5cbc0c3275c4656-0000.hkg02.containers.appdomain.cloud/superorg/sandbox/oauth/oauth2/token"
```
