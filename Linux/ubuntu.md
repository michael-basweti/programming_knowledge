### Ubuntu Reading List and commands

## Ubuntu Reading List
|Description|Link    |
| :----    | :---   |
|  | |

## Ubuntu Commands 
|Description |Command |
| -----------|----------- |  
| Get Ubuntu Version | `lsb_release -a` <br> <mark>example output: </mark> <br> `No LSB modules are available.` <br> `Distributor ID: Ubuntu` <br> `Description:    Ubuntu 18.04.6 LTS` <br> `Release:        18.04` <br> `Codename:       bionic` |
|||

### remove all files ending with xlsx

```
find . -type f -name "*.xlsx" -exec rm {} \;
```