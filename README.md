# Exam_2420 

- Darren Cheng 

## Part 1:

`sudo apt-get upgrade && sudo apt-get update`

## Part 2:

![image](https://user-images.githubusercontent.com/98194516/206562005-1cb32c53-9042-41d3-83f8-84eaca4e572b.png)

### `rC` changes the letter under the cursor to the specified 2nd letter; in this case, from V to C

![image](https://user-images.githubusercontent.com/98194516/206560782-00ab8fe7-719d-4815-aa37-3ff69b888df1.png)

![image](https://user-images.githubusercontent.com/98194516/206560565-0ee9aad9-85de-44df-a033-c529d550a21f.png)

![image](https://user-images.githubusercontent.com/98194516/206560630-76f03f96-58b7-4c38-8cec-370cd8a3312a.png)

### `i``h` to enter insert mode + add h 

![image](https://user-images.githubusercontent.com/98194516/206561486-a8cae5d3-844a-4358-a44b-77f07b033484.png)

### `i``:digit:` to enter insert mode + add :digit:

![image](https://user-images.githubusercontent.com/98194516/206561503-c268ff67-1025-4c33-8a83-89fced28fed5.png)

## Part 3:

### print logs for current boot
![image](https://user-images.githubusercontent.com/98194516/206562478-7d6d3800-2771-4e51-aa16-84a0603b3cde.png)

![image](https://user-images.githubusercontent.com/98194516/206562860-a407d692-1df8-4923-af3c-0a9efa0f9d43.png)

### priority

![image](https://user-images.githubusercontent.com/98194516/206564762-f4976df4-043d-4d18-87aa-9d462af5db49.png)

![image](https://user-images.githubusercontent.com/98194516/206564706-6c38966b-0169-4603-a561-0bb7faf4e6a8.png)


### pretty json

![image](https://user-images.githubusercontent.com/98194516/206563180-061de710-9096-4bcc-8cbb-b0f06cf9728f.png)

![image](https://user-images.githubusercontent.com/98194516/206563415-8be5311c-bbc8-4f36-a0af-1452c8c7fafb.png)

### output

![image](https://user-images.githubusercontent.com/98194516/206563384-15cd2564-65f9-4e9d-92d0-802de9b823e7.png)

![image](https://user-images.githubusercontent.com/98194516/206564415-a5c04a65-09fe-4379-8231-dcfef719ee84.png)

![image](https://user-images.githubusercontent.com/98194516/206564315-fed3f782-07c6-4cc6-acbe-64b28b61c1ae.png)


### Finished cmd

![image](https://user-images.githubusercontent.com/98194516/206565327-ada0c5cd-386c-4282-be6f-6579af5c103a.png)

## Part 4

### Create user

![image](https://user-images.githubusercontent.com/98194516/206566048-34118cf1-e7a8-4812-9caf-dbc7577a0669.png)

### Script

![image](https://user-images.githubusercontent.com/98194516/206570912-856e35c6-0cee-4b92-a78a-51b0dacf3a84.png)

### Output

![image](https://user-images.githubusercontent.com/98194516/206568648-b4e3df22-31b6-4a61-bd03-2668f7a3aa8a.png)

## Part 5:

### Make service file 

```[Unit]
Description=using test script that prints "hi Bob" to file.txt in home dir

[Service]
ExecStart=/home/vagrant/bin/testScript

[Install]
WantedBy=multi-user.target
```

### Move service file to /lib/systemd/system

![image](https://user-images.githubusercontent.com/98194516/206572797-68af4b31-3b05-4c2f-929e-b3ace8cfb6fc.png)

### enable + start service

![image](https://user-images.githubusercontent.com/98194516/206572993-b07a495a-6a1f-4005-a18b-c0f3bad55cbe.png)



