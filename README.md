![GitHub contributors](https://img.shields.io/github/contributors/dracoYT/iMage) ![Website](https://img.shields.io/website?url=https%3A%2F%2Fdracoyt.github.io%2F)
# iMage
(**This Project still in development**) 


## How to install
Clone this repo.
```shell
$ git clone https://github.com/dracoYT/iMage
```
Launch **setup.sh** and wait until installation.

![enter image description here](https://github.com/dracoYT/iMage/blob/master/image.png)

Then if you want to update open **update.sh** else you can 
```batch
> image -setup "own/"
```

Output:
```batch
Installed:
- need update: no
- version: 2.0.1
- update link: dracoyt.github.io/mt/im
```
(This link does't work)
## Usage

       
       
iMage -[setup, run, update, help, burn] <args>
  
  Setup: install an aplication. Example. image -setup "loacal:./out/app.img-comp"
  Run: Run an installed aplication. Example. imqage -run "app"
  
  Update: Update a aplication (if the aplication dont have lasted vesions you'll get an error)  Example. image -update "app" "version" "link in case it dont have" (if your app  is local use: local:out/app-v2.img-comp&%update%)
  
  BURN: A developer tool. The example is in the **Burn** section.
  
  ## (Future)  in App integration
  
  Batch:
  ```batch
  > image b-[args]
  ```
  Batch silent: 
  ```batch
  > bs-[args]
  ```
  
  JavaScript:
  
  Still indev.
  
  HTML
  
  Still indev
  
  ## How to burn (This feature is in development)
  ```batch
  > image -burn "main app name" "Depends dir" "Install message / update" 
  ```
  Mesage contnent:
 (i'm Still in writtng)
          
