# HEPIC Kibi Dashboards (demo)

### Pre-Install
```
 virtualenv env
 . env/bin/activate
 pip install -r requirements.txt
```
# BACKUP example
```
  python kibana_dump.py --url 'http://localhost:9200' --dir output
```
# RESTORE example
```
  ./load.sh -url http://localhost:9200 -user admin:somepassword
```
