# Lotteria Fanpage Analysis

## Giới thiệu  
Dự án này phân tích dữ liệu từ fanpage Lotteria giai đoạn 2012-2022, nhằm hiểu rõ hiệu suất bài đăng, xu hướng nội dung và mức độ tương tác của người dùng.

## Mục tiêu phân tích  
1. Phân tích sự phát triển của fanpage từ năm 2012 đến 2022.  
2. Đánh giá hiệu suất bài đăng dựa trên mức độ tương tác của người dùng.  
3. Xác định xu hướng và từ khóa ảnh hưởng đến sự tương tác.  

## Cấu trúc thư mục  
Lotteria-Fanpage-Analysis/
│-- data/               # Chứa dữ liệu gốc
│-- scripts/            # Chứa code R Markdown
│-- reports/            # Chứa báo cáo xuất ra
│-- README.md           # Mô tả dự án chi tiết


## Công nghệ sử dụng  
- R  
- ggplot2, dplyr, readxl, tidyverse  
- Phân tích dữ liệu & trực quan hóa  

## Cách sử dụng  
1. Cài đặt thư viện cần thiết trong R:  
install.packages(c("ggplot2", "dplyr", "readxl", "tidyverse")) và các thư viện liên quan.

2. Chạy file R Markdown để tạo báo cáo:
rmarkdown::render("scripts/R-Lotteria-Fanpage-Analysis.rmd")
