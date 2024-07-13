Đây là setup để chạy 1 server PaperMC 1.21 trên Github Codespaces. Báo trước là cái này ko nên dùng để chơi lâu dài vì 2 core 8gb ram max là 60 tiếng / tháng và 4 core 16gb ram max là 30 tiếng / tháng. Nếu muốn thử thì hd đây :
1. Fork cái repo này
2. Ấn vô code -> codespaces -> Create codespace on main
3. Thoát cái tab codespaces, vô lại cái codespaces, ấn 3 chấm r tắt cái Auto delete codespaces và chỉnh machine type cũng ở đấy. Rồi vô lại codespaces
4. (Tùy) Nếu ko muốn chơi bản 1.21 thì xóa cái file jar ở main đi dùng lệnh "wget (link file paper.jar)". [Chỗ có link down paper.jar ở dạng json](<https://qing762.is-a.dev/api/papermc>)
5. Nếu 8gb ram : java -Xmx6G -Xsm5G -jar (file jar paper) --nogui
      16gb ram : java -Xmx14G -Xsm12G -jar (file jar paper) --nogui
6. Lúc server chạy thì sẽ có cái link playit.gg, giữ ctrl r click vô, create account -> use guest account -> chờ r ấn add agent -> chờ tiếp và boom Tunnel Created: (cái này random).joinmc.link <= cái này sẽ là ip server
7. Mở Minecraft lên r copy cái link này để vô thôi :D
8. Chơi xong thì vô console r dùng lệnh stop để dừng server, tìm cái nút khi hover ghi là source control (nó ở bên trái), ấn commit, yes, ghi cái j cũng đc trong COMMI_EDITMSG, sync changes, yes r thoát tab, vô trang github đã fork r vô codespaces r stop codespaces (để tránh nó quá 30 hoặc 60 tiếng lúc nào ko biết 🐧). Từ lần 2 bật server trở đi thì ip sẽ khác cái đầu nhưng ip mới nó sẽ hiện trong console nên ko phải lo
