# Mô tả sơ lược về dữ liệu
Đây là tập dữ liệu mô tả các đặc tính vật lý của nấm, cùng với nhãn phân loại có độc hoặc ăn được (thuộc tính class đầu tiên: p (poisonous) – có độc, e (edible) – ăn được).
* Số lượng mẫu: 8124.
* Số lượng thuộc tính: 22.
* Kiểu của mỗi thuộc tính: nomial.
* Thuộc tính thiếu giá trị: stalk-root, số lượng mẫu bị thiếu giá trị: 2480 (31%).
* Sự phân bố của dữ liệu vào các phân lớp khá cân bằng. Số lượng các phân lớp không áp đảo nhau (imbalanced).
* Ta dùng filter > unsupervised > attribute > ReplaceMissingValues để điền các giá trị thiếu.

Nhờ mô hình phân lớp (classification) ta có thể phân biệt được đâu là nấm độc, đâu là nấm ăn được chỉ thông qua một số đặc điểm nhận diện qua mùi và màu sắc.

Về đặc điểm mùi, nấm nào ăn được thường có mùi hạnh nhân và mùi hoa hồi, nấm độc thường có mùi hôi, tanh, và cay. Còn đặc điểm màu sắc, chỉ có nấm màu xanh lá cây mới ăn được, các loài nấm có màu loè loạt như cam, vàng, tím đều là nấm độc.
