# AISE-dataset
###
Đây là bộ dữ liệu phục vụ cho bài toán Software Defect Prediction,Bug Localization
###
FLIE SDP:  
###
File SDP là dạng dữ liệu data software metric,3 bộ dữ liệu thu thập đượ(NASA,Eclipse,Promise(Apache)).  
Theo như tìm hiểu được thì có tổng cộng 48 bộ Promise 13 bộ Nasa (bộ Eclipse do có nhiều nhóm làm nên chưa thống kê được)  
Hiện đã thu thập được 41 bộ Promise và 13 bộ Nasa, các tập còn lại đang trong quá trình bóc tách(đang cập nhật)  
###
FILE SOURCE CODE OF PROMISE:  
###
File Source Code of Promise là dạng file nguồn của các bộ data Promise(source file trực tiếp)  
Do link các bài báo Citation đã sập, nhóm dùng tạm file soure code được backup  
Theo xu hướng gần đây khi áp dụng các mô hình học sâu, người ta thường kết hợp software metric và trích xuất AST(abstract syntax tree) cho mô hình nên chúng ta cần phải phân tích AST từ source code.  
Gợi ý: các bạn có thể sử dụng package của python javalang(các bài báo đều nói sử dụng package này để phân tích AST)  
Link package: https://github.com/c2nes/javalang  
Link hướng dẫn từ TQ: https://its401.com/article/qq_35294564/115342407  
###
FILE BUG LOCALIZATION DATA:  
###
File Bug Localization Data là dạng data phục vụ bài toán Bug Localization:  
Mỗi tập dữ liệu đều có file bug và file source  



**GOOD LUCK**
