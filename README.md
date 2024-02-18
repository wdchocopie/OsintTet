![image](https://github.com/wdchocopie/OsintTet/assets/81132394/e2c2560d-0213-467b-aebd-f0839698bde3)# OsintTet
Bài Osint tết https://www.facebook.com/ehc.fptu/posts/pfbid0492wFdoqYcZ67uQhrviAYFfrfxr56VzViZDK3xMjynzS2zX4hW8Du4dma9pD9beQl
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/047cefc6-a4e6-4c5b-a14d-46e01ce949f1)
Tại đây cái đầu tiên mình nhận được từ thử thách
Mình để ý tới phần M1ssgr4ndvi3tnam in mờ mờ ở trên khung số 2, có dấu @ nên mình đã thử tìm nó sử dụng tool trong osint framework > username > whatsmyname
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/d59825d9-a1e5-410e-970f-7c79bf1edb5b)
Tại đây mình thấy 1 tài khoản pinterest, mình thử ngó qua nó xem
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/871e305d-f33d-4101-b1be-7a081e0a8288)
Vì vừa nãy mình đã có ảnh từ trên facebook nên mình sẽ check thửu ảnh còn lại
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/abab613a-3e8d-4a76-af59-07301e8f9855)
Vì ảnh này có 2 tài khoản là M1ss Gr4nd và nhi3n là 2 cái tên đáng chú ý nên mình sẽ search thử nó trên whatsmyname thì có kết quả như sau
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/75f8fc15-25f3-475c-b27b-087d6fcecff8)
tại đây ta thấy 1 tài khoản github
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/2849d91a-dcbf-469c-aedc-603a89309c18)
Tại đây mình thử truy cập vào file readme.md và thấy các con số không vượt quá số dòng
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/4ae533ac-0da1-4d22-aa11-4b053112bcac)
Mình thử xuống từng dòng 1 trong raw code xem nó là gì thì thấy đoạn đằng sau của nó có dạng 1 link youtube https://www.youtube.com/watch?v=xxxxxxxxxx[1 chữ cái], mình quyết định sẽ thử thay các chữ vào theo thứ tự ở đoạn xxxx thì được kết quả https://www.youtube.com/watch?v=J6gDm5yvYy0
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/b08f2a51-3137-48ee-93c8-f278ec68445d)

Mình thử vào link đó nhưng chả hiểu gì nên quyết định tìm tiếp ở github. Khi mình mở phần lịch sử commit thì file này có tận 4 lần chỉnh sửa
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/95d70762-99e3-4ffa-9956-4172e8e349a5)
Sau khi mò mẫm 1 lúc, mình thấy ở đoạn này khá khả nghi vì nhìn nó giống 1 dạng link
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/ee69f969-bb49-43c1-bcce-3db6494b172b)
Mình tiến hành thử xem nó là dạng mã hóa nào bằng cách thử. Sau 1 hồi thử thì nó hiện ra A-Z rot 16
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/e23115ba-9418-4da0-bfa8-847b743b8268)
Tiến hành truy cập vào sites.google.com/view/m1ssgr4ndvietnam/main
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/a1ba6f69-32dd-4b29-be54-4c45f68daa18)
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/ab12ea59-2b11-4880-831d-07cd4a48c3f1)
Thấy ở đây nó có để x (twitter) nên mình thử vào twitter và search cái này thì ra 1 tài khoản. tạm thời mình chưa ra gì nên để tạm đây
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/050abbac-2d3c-4c52-8a4a-c3a7d304e6fb)
Quay lại phần website, Mình thấy contact mail for work thì mình thử đoán mail là m1ssgr4ndvi3tnam@gmail.com thì ai dè ra thật. Mình thử gửi 1 cái mail về thì nó trả về mail này
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/b9953e64-a5fa-4242-adbb-bac69fa1382c)
Mình thử dịch đoạn twrLwcA!J0}bH0*b2C0 bằng dencode thì nó ra được 1 phần của flag 	
EHC{H4pPy_N3w_Y3ar_
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/f6a98ca5-a570-43c4-a471-e0bf4bab3a0e)
Tiếp tục với cái mail thì mình cũng thấy 1 link discord, mình thử join vào và thấy server như sau
![image](https://github.com/wdchocopie/OsintTet/assets/81132394/f7427c1a-d25e-4f4f-9a66-ce053af8ce69)

