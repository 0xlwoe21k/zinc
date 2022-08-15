### 0x1 new CLI feature
new CLI feature. that can import data by CLI not http.
```
 -bulkpath string
        bulk import data path
 -index string
        index
  -server
        server
```
### 0x2 usage
```
winddow 
set ZINC_FIRST_ADMIN_USER=test
set ZINC_FIRST_ADMIN_PASSWORD=test
.\zinc.exe -index test -bulkpath "C:\Users\admin\Desktop\olympics.ndjson"

linux
export ZINC_FIRST_ADMIN_USER=test
export ZINC_FIRST_ADMIN_PASSWORD=test
./zinc.exe -index test -bulkpath "~/olympics.ndjson"
```

### 0x3 build zinc 
```
[root@localhost  web]# npm install 
[root@localhost  web]# npm run build

[root@localhost  zinc]# go mod tidy
[root@localhost  zinc]# go build

```
