# SNN-research

## Papers collection
*   [📂 CNNs](./CNNs/)
*   [📂 EfficientCNNs](./CNNs/Efficient)
*   [📂 EfficientSNNs](./EfficientSNNs/) (đang cập nhật)
*   [📂 SNNs](./SNNs/) 
*   [📂 SURVEY](./SURVEY/) (2022)
*   [📂 Transformers base](./Transformers%20base/)

## Định hướng nghiên cứu
Mạng nơ-ron xung (Spiking Neural Networks-SNNs) là một hướng tiếp cận lấy cảm hứng từ sinh học, trong đó thông tin được truyền dưới dạng các xung rời rạc theo thời gian. Nhờ cơ chế xử lý theo sự kiện và hoạt động không đồng bộ, SNNs trên lý thuyết có tiềm năng tiết kiệm năng lượng tốt hơn so với các mạng nơ-ron nhân tạo truyền thống (ANNs), đặc biệt khi triển khai trên phần cứng chuyên dụng.

Các mạng nơ-ron tích chập (Convolutional Neural Networks-CNNs) vẫn là kiến trúc tiêu chuẩn cho các bài toán computer vision nhờ độ chính xác và khả năng trích xuất đặc trưng mạnh mẽ. Việc kết hợp CNNs với SNNs mở ra hướng tiếp cận lai (hybrid), nhằm tận dụng ưu điểm về hiệu năng của ANN và hiệu quả năng lượng của SNN.

Tuy nhiên, SNNs hiện vẫn chưa đạt được hiệu năng tương đương ANN trong nhiều bài toán thực tế. Nguyên nhân chính đến từ cơ chế spike rời rạc, gây khó khăn cho việc huấn luyện bằng các phương pháp dựa trên gradient. Vì vậy, các nghiên cứu hiện nay tập trung vào việc cải tiến cơ chế học của SNNs, chẳng hạn như surrogate gradient và các phương pháp huấn luyện phù hợp với dữ liệu theo thời gian.

Song song với đó, Neuromorphic Computing là một hướng nghiên cứu phần cứng lấy cảm hứng từ sinh học, được thiết kế để xử lý thông tin theo mô hình sự kiện. Các hệ thống này đặc biệt phù hợp với SNNs và các kiến trúc lai ANN–SNN, cho phép khai thác hiệu quả tính thưa, tính không đồng bộ và tiềm năng tiết kiệm năng lượng. Nghiên cứu về SNNs và neuromorphic computing vì vậy mang tính bổ trợ lẫn nhau, hướng tới xây dựng các hệ thống AI hiệu quả, linh hoạt và tiết kiệm năng lượng hơn trong tương lai.

Một số hướng nghiên cứu chính nhằm cải thiện hiệu năng của SNNs:

* Mô hình neuron: thiết kế các neuron spiking có cơ chế hoạt động tốt hơn, cân bằng giữa tính sinh học và khả năng tính toán.

* Cơ chế ngưỡng phát xung (thresholding): nghiên cứu ngưỡng tĩnh, ngưỡng động và các cơ chế thích nghi nhằm cải thiện độ ổn định và khả năng biểu diễn.

* Cơ chế học và lan truyền gradient: phát triển các phương pháp surrogate gradient và các biến thể của backpropagation phù hợp với spike rời rạc.

* Hàm loss cho dữ liệu theo thời gian: xây dựng các hàm loss phản ánh đúng đặc tính temporal của SNNs, thay vì chỉ dựa trên đầu ra tĩnh.

* Chiến lược mã hóa thông tin: nghiên cứu các phương pháp mã hóa như rate coding, temporal coding, hoặc population coding.

* Kiến trúc mạng và mô hình lai (hybrid): kết hợp ANN và SNN nhằm tận dụng ưu điểm của cả hai hướng tiếp cận.

* Triển khai trên phần cứng neuromorphic: ánh xạ mô hình SNN và hybrid lên các nền tảng phần cứng hướng sự kiện để đạt hiệu quả năng lượng cao.

