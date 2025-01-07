# NASSCOM-VSD-Phydesign
#Day-1-OPENLANE_SKYWATER130nm-openEDA
Use of docker for openlane.
We use interactive mode for line by line interactive flow, aids to understand step by step.

![image](https://github.com/user-attachments/assets/88faeb4e-8d5a-4d3d-819c-f6af626c557d)
![image](https://github.com/user-attachments/assets/94bd4482-9fd6-4403-adb6-bbfd4349f345)

cell and layer level information combined in merged lef file

![image](https://github.com/user-attachments/assets/007b9021-9372-46b8-b0b5-0ca5d9977e42)

run_synthesis uses yosys and abc for synthesis

![image](https://github.com/user-attachments/assets/1e4fb0e2-c53c-4fdb-b30c-94b0ef9e2e27)

Statistics report helps to find the number of various components/cells inside.


![image](https://github.com/user-attachments/assets/9d3340ba-ab52-460e-aa81-68e60a162ec4)

Helps in finding flop ratio

![image](https://github.com/user-attachments/assets/d862f3c9-1924-43c9-b56a-4a9b516bebb7)

![image](https://github.com/user-attachments/assets/531716c5-24fc-4b59-a4fd-574f1e5d280c)


Flop ratio = Number of D Flip flops / Total Number of Cells
            = 1613/14876
            =10.8426%


src contains the verilog file and sdc(design constraint)

verilog file contains rtl from design => rtl netlist


config.tcl bypasses any changes made from default

![image](https://github.com/user-attachments/assets/764f57bb-4944-4a1c-943b-8a43d917f241)

netlist holds rtl

![image](https://github.com/user-attachments/assets/6bc3d855-36c0-404b-8d22-e5976db1ab98)

To view 
![image](https://github.com/user-attachments/assets/bb50919c-f0be-47a7-a223-7df7da330395)
![image](https://github.com/user-attachments/assets/5994ac22-4d92-4bb3-bb27-b5a353102170)
![image](https://github.com/user-attachments/assets/05060c1c-0dfc-4e69-9bf1-3b4732a45723)
![image](https://github.com/user-attachments/assets/8d888585-c09c-4b20-b928-435bd5e6549a)

 
![image](https://github.com/user-attachments/assets/b552e621-ff7d-44d0-a627-08cb0628728d)

![image](https://github.com/user-attachments/assets/89c64189-d94c-4547-99ab-18ac929bf218)

![image](https://github.com/user-attachments/assets/cdf5715f-7199-4e54-883a-361733628585)




# Day-2
Utilization Factor = Area occupied by netlist/Total area of the core 
                   
                     
Aspect Ratio = Height of Core/Width of Core
               
When the aspect ratio is 1, the chip is a square. When it is not 1,its a rectangle.

Target density how close or how far your want your celss to be placed

Configuration file
![image](https://github.com/user-attachments/assets/038a78d6-670b-4790-b4c9-449e3c05931f)
![image](https://github.com/user-attachments/assets/cf2d22fa-57b7-44bb-9678-2ee4158c895d)
![image](https://github.com/user-attachments/assets/90db327b-5018-49b6-9885-eca2d908210a)

Floorplan
![image](https://github.com/user-attachments/assets/145d3a27-2068-4264-bad0-fa8bf8952cf3)

![image](https://github.com/user-attachments/assets/61455389-60f1-4f73-97aa-61705932655d)
![image](https://github.com/user-attachments/assets/52686154-341a-4bb9-a03e-36d09b38b7b9)

![image](https://github.com/user-attachments/assets/b6b0b189-0061-48da-bfe9-190ea48c8d56)

![image](https://github.com/user-attachments/assets/9dbbaf99-ba5e-4fa4-a83c-83f443537738)

Using magic

![image](https://github.com/user-attachments/assets/f25f8296-b2e7-4408-9675-9516a7818c73)

