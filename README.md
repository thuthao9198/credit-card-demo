# Credit Card Defaulter Prediction Demo

## Nội dung
  * [Demo](#demo)
  * [Tổng quan](#tongquan)
  * [Thông tin tập dữ liệu](#thongtintapdulieu)
  * [Xây dựng demo](#xây dựng demo)
  * [Cây thu mục](#caythumuc)  
  * [Công cụ và thư viện được sử dụng](#congngheduocsudung)
  
  

## Demo
Link: [https://data-mining-g3.herokuapp.com/](https://data-mining-g3.herokuapp.com/)

[![](https://imgur.com/a/NN45ZfN.png)](https://data-mining-g3.herokuapp.com/)


## Tổng quan
Đây là mô hình phân loại cho một tập dữ liệu phổ biến nhất, dự đoán về tình trạng vỡ nợ thẻ dụng của tháng tiếp theo dựa trên dữ liệu nhân khẩu học và hành vi 6 tháng vừa qua của khách hàng.

## Thông tin tập dữ liệu
Link: [https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients/](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients/)

Đồ án sẽ không thể thực hiện được nếu như không có tập dữ liệu này. Tập dữ liệu này chứa các thông tin về thanh toán mặc định, các yếu tố nhân khẩu học, dữ liệu tín dụng, lịch sử thanh toán và bảng sao kê hóa đơn của các khách hàng sử dụng thẻ tín dụng ở Đài Loan từ tháng 4 năm 2005 đến tháng 9 năm 2005.

## Xây dựng demo
 
 ─Đào tạo mô hình phân loại sử dụng RandomForestClassifier để dự đoán về tình trạng vỡ. nợ thể tín dụng tháng tiếp theo của khách hàng.
─Làm sạch dữ liệu.
─Áp dụng mô hình phân loại máy học. 
─Xây dụng ứng dụng web trên Heroku.
─Tải demo lên Github.
─Nhận thông tin của khách hàng từ ứng dụng Web.
─Hiển thị dự đoán.

## Cây thư mục
```
├── templates 
│   └── index.html
├── app.py
├── credit-card-default.csv
├── credit_default_prediction.py
├── model.pkl
├── Procfile
├── README.md
└── requirements.txt
```

## Công cụ và thư viện được sử dụng

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://numpy.org/images/logos/numpy.svg" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)    [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=150>](https://scikit-learn.org/stable)   [<img target="_blank" src="https://www.statsmodels.org/stable/_images/statsmodels-logo-v2-horizontal.svg" width=170>](https://www.statsmodels.org)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=150>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=200>](https://gunicorn.org) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)      [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org)

[<img target="_blank" src="https://jupyter.org/assets/nav_logo.svg" width=150>](https://jupyter.org)

