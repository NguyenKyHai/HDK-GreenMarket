# HDK-GreenMarket 
## Link project: https://green-market-hdk-izrrhd2plq-uc.a.run.app 
### Link báo cáo: https://drive.google.com/file/d/1BF5S9y1J3qSlA_rR2zJ_jWoDyNGM4iSQ/view?usp=sharing

Project được xây dựng bằng công nghệ MERN (MongoDB, Express, ReactJS và NodeJS) được deploy bằng Google Cloud Run bằng cách sử dụng Docker image.\
Link backend: https://github.com/TNQuocKhanh/API-MERN .\
Link front-end: https://github.com/DiepThaiDuong-19110009/frontend-TLCN .

# Triển khai ứng dụng trên Google Cloud Platform
Build image bằng Dockerfile --> Push image to Google Container Registry --> Deploy to Google CLoud Run .\
Link back-end: https://green-node-app-izrrhd2plq-uc.a.run.app/api/product .\
Link project sau khi deploy: https://green-market-hdk-izrrhd2plq-uc.a.run.app 

# Hướng dẫn cách khởi chạy dự án
> Cài đặt IDE Visual Studio Code, Git, NodeJS, npm (hoặc yarn) 
  * Chọn thư mục cần chạy dự án, cmd vào thư mục đó
  * Chạy lệnh: `git clone https://github.com/TNQuocKhanh/API-MERN.git` với back-end </br>
    Và `git clone https://github.com/DiepThaiDuong-19110009/frontend-TLCN` với front-end
  * Chạy lệnh: `npm install` (nếu lỗi do xung đột phiên bản thì chạy lệnh: `npm install --force`)
  * Chạy lệnh: `npm start` để chạy dự án 
> Lưu ý: Cần chạy back-end trước để có API cho front-end  
