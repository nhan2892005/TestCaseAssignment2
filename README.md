# Bộ Testcase nhỏ cho Bài tập lớn 2 - Kỹ Thuật lập trình - Trường Đại học Bách Khoa TP.HCM
## Giới thiệu:  
- Bộ test sẽ kiểm tra việc khởi tạo và truy cập vào các class bằng class TestStudyInPink

- Tôi sẽ chia bài tập lớn này thành 9 phần:

    - Phần 1: Khởi tạo được Bản đồ. Test 1 tới 10
    - Phần 2: Khởi tạo được đối tượng Sherlock và hiện thực đúng các phương thức. Test 11 tới 20
    - Phần 3: Khởi tạo được đối tượng Watson và hiện thực đúng các phương thức. Test 21 tới 30
    - Phần 4: Khởi tạo được đối tượng Criminal và hiện thực đúng các phương thức. Test 31 tới 40
    - Phần 5: Khởi tạo được ArrayMovingObject và hiện thực đúng các phương thức. Test 41 tới 50
    - Phần 6: Khởi tạo được các đối tượng Robot và hiện thực đúng các phương thức. Test 51 tới 60
    - Phần 7: Khởi tạo được các đối tượng BaseItem và hiện thực đúng các phương thức. Test 61 tới 70
    - Phần 8: Khởi tạo được các đối tượng BaseBag và hiện thực đúng các phương thức. Test 71 tới 80
    - Phần 9: Chạy chương trình hoàn chỉnh bằng phương thức `run` trong class `StudyPinkProgram`. Test 81 tới 90 (Tuy nhiên test này vẫn chưa hoàn thành và chưa sử dụng được)

- Lưu ý: Đây là bộ test tạo nên từ code của mình, vì vậy mọi kết quả đều không hoàn toàn chính xác.
  Tuy nhiên, nếu bạn mắc lỗi ở 1 test nào đó, hãy liên hệ cho tôi và cùng debug.

## Hướng dẫn sử dụng bộ test
- Bước 1: Các bạn clone repo của mình về local theo hướng dẫn sau: [cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

- Bước 2: Thêm 2 file bài bài làm `study_in_pink1.cpp` và `study_in_pink1.h`

- Bước 3: Các bạn mở Terminal
  (dùng bash hoặc các OS UNIX để chạy lệnh vì các lệnh mình viết sẽ không chạy được ở Windows).
  Các bạn có thể kết nối với WSL Ubuntu của Microsoft để không cần phải set up máy ảo.
  ![Terminal WSL Ubuntu](https://github.com/nhan2892005/BTL1_KTLT_HCMUT_K23_19-02-2024---test/assets/143471539/36842a20-4502-4da1-83bd-396f6575878f)
  
  ![Terminal bash có sẵn ở VSC](https://github.com/nhan2892005/BTL1_KTLT_HCMUT_K23_19-02-2024---test/assets/143471539/2e2189dd-e10d-46dc-a6b8-f7819ad3fed3)
  Nếu các bạn lười connect với WSL thì hãy dùng bash

- Bước 4: ở thư mục gốc (bạn vừa clone về) chạy lệnh
  
  ```
   g++ -o main main.cpp studyinpink2.cpp
  ```
  Sau đó chạy lệnh `./main`
  Nếu muốn chạy kiểm tra từng task thì nhập theo 1 trong 2 cú pháp sau đây:
  ```
  ./main <số bắt đầu của task> <số kết thúc của task>
  VD: ./main 1 10
  hoặc
  ./main <số của test>
  VD: ./main 15
  để kiểm tra test 15
  ```
  
  ![Chạy lệnh để bắt đầu test](https://github.com/nhan2892005/BTL1_KTLT_HCMUT_K23_19-02-2024---test/assets/143471539/0485ffbf-46ec-464d-98cd-b8f04b3c4427)

- Bước 5: Nhận kết quả

- Bước 6: Đặt sao cho repo này (hihi)

## Lời kết
- Như đã nói, bộ test không sử dụng bất kì nguồn tài nguyên nào khác ngoài ví dụ của đề và code của mình. 
Vì vậy, test chỉ giúp chúng ta dễ dàng debug, so sánh kết quả với nhau và tìm ra giải pháp tốt hơn, không đảm bảo được tính đúng đắn
cũng như khi test và submit ở môi trường chấm điểm trên LMS

- Các bạn nên đọc kỹ các yêu cầu, đặc biệt là phần `7 Một số quy định khác` và phần `8 Gian lận` của đề, nhằm tránh sơ suất trong quá trình làm bài

## Liên hệ và đóng góp
[Email](nhan.nguyen2005phuyen@hcmut.edu.vn)

[Facebook](https://www.facebook.com/phucnhancshcmut/)

[Website](http://phucnhan289.great-site.net/1/Ph%C3%BAc-Nh%C3%A2n.html) 

[LinkedIn](linkedin.com/in/phúc-nhân-nguyễn-778b26275/)

Chúc các bạn hoàn thành bài tập lớn thật tốt

Nhân