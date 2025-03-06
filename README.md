# Git-merge-BackEnd

git สรุปคำสั่ง
step merge-ไปที่ D:DEV\DEVOPS\ws\ows_back
-git fetch
-git check out fix/ChangestatusCompany
-git checkout develop เพื่อให้เราอยู่ใน Develop ก่อน
-git status เพื่อดูว่าเรายังอยู่ที่ branch develop ไหม
-git  merge -m "massage หัว ใน web git  #2025030numberofversion - fix/changeStatusCompany" fix/changeStatusCompany
-new issue บน ows_back ของ web git    เอาผลลัพธ์ที่ merge ใส่ใน issue
-ใส่ label ในหน้า new issue เช่น develop ,release
-git push
สมมุติมี ให้ merge อีกเส้น เช่น hf/CustomerLocation

-git checkout hf/CustomerLocation
-git checkout develop 
-git status
-git merge -m "[MC_TOLC] #20250306 - hf/CustomerLocation" hf/CustomerLocation
-เอาผลลัพธ์จาก git merge ใส่ต่อจาก New issue เส้น - fix/changeStatusCompany
-git push


step  Release 
merge release กับ develop
-git checkout release
-git merge -m "[MC_TOLC] #20250306  - develop"  develop
เอาผลลัพธ์จาก git merge comment ใน New issue
-git push 
step สุดท้าย เปิด Visual studio  1.Build 2.Re build 3.ถ้ามี Error ก็ แก้แล้ว Build ใหม่ 4.ไปที่ project แล้ว publish 
![image](https://github.com/user-attachments/assets/1ea64060-2bc5-4bc3-8265-42d272d3d2be)
