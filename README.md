### drive
---
https://github.com/odeke-em/drive

```
```

```sh
cat << ! ~/.bashrc
export GOPATH=\$HOME/gopath
export PATH=\$GOPATH:\$GOPATH/bin:\$PATH
!
source ~/.bashrc

go get -u github.com/odeke-em/drive/cmd/drive


drive init ~/gdrive
drive init --service-account-file <gsa_json_file_path> ~/gdrive
drive push -h
cat << ! >> ~/.driverc
export=doc,pdf
depth=100
no-prompt=true
cat << $>> .driveignore
\.gd$
\.so$
\.swp
$

drive pull -decryption-password '$JiME5Umf' influx.txt
drive pull -matches vines docx
dirve pull -force
drive pull photos/img001.png docs
drive pull -id xxxxxxxxx
drive pull -depth 2 heavy-files summaries
drive pull -depth -1 all-my-files
drive pull -starred
drive pull -starred -matches content
drive pull -starred -all
drive pull -starred -all -trashed
drive pull -fiels a1/b2
drive pull -directories tf1
drive pull -ignore-checksum=false
drive about
drive about -features -quota
drive help
drive help push


```

```
```


