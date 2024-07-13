Đây là setup để chạy 1 server PaperMC trên Github Codespaces
Báo trước là cái này ko nê dùng để chơi lâu dài vì 2 core 8gb ram max là 60 tiếng / tháng
                                                   4 core 16gb ram max là 30 tiếng / tháng
Nếu muốn thử thì hd đây :
1. Fork cái repo này
2. Ấn vô code -> codespaces -> Create codespace on main
3. (Tùy) Nếu ko muốn chơi bản 1.21 thì xóa cái file jar ở main đi dùng lệnh "wget (link file paper.jar)". [Chỗ có link down paper.jar ở dạng json](<https://qing762.is-a.dev/api/papermc>)
4. Nếu 8gb ram : java -Xmx6G -Xsm5G -jar (file jar paper) --nogui
      16gb ram : java -Xmx14G -Xsm12G -jar (file jar paper) --nogui
