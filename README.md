# Volatility: Memory Analysis

<h2>Description</h2>
In this Digital Forensics task, I installed volatility and used python3 to create a virtual environment to run volatility on a windows 10 memory dump file.  

<h2>Languages and Utilities Used</h2>

- <b>python3</b>
- <b>volatility</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b> 

<br />
<br />
Installed volalilty 3 using "git clone --branch stable https://github.com/volatilityfoundation/volatility3" then ran python3 to create a virtual environment within the volatility directory. 

![1) installing and avctivating python3 venv](https://github.com/user-attachments/assets/8b3acbb0-8121-41f2-b0e3-38b4731816d5)

<br />
<br />
Installing the requirements to run volatlity using "pip install -r requirements.txt" within the volatility directory. 

![2) installing requirements for volatility in python3](https://github.com/user-attachments/assets/69ee7e84-2915-4bc6-83cc-ab7e5b2d223e)

<br />
<br />  
Creating a sha256 hash of the win10.vmem memroy dump file. 

![3) sha256sum of win10 memdump](https://github.com/user-attachments/assets/fb6f87dd-1968-4291-8156-0b355d131fc9)

<br />
<br />
Running volatility on the win10.vmem file to enumerate system details. 

![4) runing volatility on win10 memdump](https://github.com/user-attachments/assets/28339dce-f331-45bf-8341-406c7d02d3cd)

<br />
<br />
