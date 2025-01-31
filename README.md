# Lotteria Fanpage Analysis

## Giới thiệu  
Dự án này phân tích dữ liệu từ fanpage **Lotteria** giai đoạn **2012-2022**, nhằm hiểu rõ hiệu suất bài đăng, xu hướng nội dung và mức độ tương tác của người dùng.

## Mục tiêu phân tích  
1. **Phân tích sự phát triển của fanpage từ năm 2012 đến 2022.**  
2. **Đánh giá hiệu suất bài đăng dựa trên mức độ tương tác của người dùng.**  
3. **Xác định xu hướng và từ khóa ảnh hưởng đến sự tương tác.**  

## Cấu trúc thư mục  
```plaintext
Lotteria-Fanpage-Analysis/
├── data/               # Chứa dữ liệu gốc
├── scripts/            # Chứa code R Markdown
├── reports/            # Chứa báo cáo xuất ra
└── README.md           # Mô tả dự án chi tiết
```

## Công nghệ sử dụng  
- **Ngôn ngữ:** R  
- **Thư viện:** ggplot2, dplyr, readxl, tidyverse  
- **Ứng dụng:** Phân tích dữ liệu & trực quan hóa  

## Cách sử dụng  

### 1️⃣ Cài đặt thư viện cần thiết trong R  
Chạy lệnh sau trong **RStudio** để cài đặt thư viện:  
```r
install.packages(c("ggplot2", "dplyr", "readxl", "tidyverse"))
```

### 2️⃣ Chạy file R Markdown để tạo báo cáo  
Dùng lệnh sau để **render file `.rmd`**:
```r
rmarkdown::render("scripts/R-Lotteria-Fanpage-Analysis.rmd")
```

## Liên hệ  
- **Tác giả:** [Lê Huỳnh Thúy Vy]  
