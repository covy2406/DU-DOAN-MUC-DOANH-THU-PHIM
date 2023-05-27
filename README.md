# Dự đoán mức doanh thu phim

## ⚒ Các thư viện cần cài đặt

| Thư viện            | Lệnh cài đặt                    | Tài liệu                                               |
| :------------------ | :------------------------------ | :----------------------------------------------------- |
| `bs4`               | `pip install bs4`               | https://www.crummy.com/software/BeautifulSoup/bs4/doc/ |
| `sklearn`           | `pip install -U scikit-learn`   | https://scikit-learn.org/stable/                       |
| `pandas`            | `pip install pandas`            | https://pandas.pydata.org/docs/                        |
| `seaborn`           | `pip install seaborn`           | https://pandas.pydata.org/docs/                        |
| `numpy`             | `pip install numpy`             | https://numpy.org/doc/stable/                          |
| `scipy`             | `pip install scipy`             | https://docs.scipy.org/doc/scipy/                      |
| `category_encoders` | `pip install category_encoders` | http://contrib.scikit-learn.org/category_encoders/     |

## 🚀 Trình tự chạy chương trình

Crawl dữ liệu từ trang web

```bash
  crawling.ipynb
```

Folder lưu trữ các file dữ liệu thô:

```bash
  raw_data/
```

File lưu trữ dữ liệu thô: 

    - 1000 samples

```bash
  SmallDS_raw.csv
```

    - 10000 samples

```bash
  BigDS_raw.csv
```

Folder lưu trữ các file dữ liệu được làm sạch:

```bash
  clean_data/
```

File lưu trữ dữ liệu được làm sạch: 
    - 1000 samples

```bash
  SmallDS_clean.csv
```

    - 10000 samples

```bash
  BigDS_clean.csv
```

File main chứa tất cả các hàm xử lí, chuẩn hóa, chia dữ liệu và mô hình hóa: 
    - 1000 samples

```bash
  main_smallds.ipynb
```

    - 10000 samples

```bash
  main_bigds.ipynb
```
