# Bi-Bimodal Modality Fusion for Correlation-Controlled Multimodal Sentiment Analysis

Bi-Bimodal Fusion Network (BBFN):

Ý tưởng chính:
Tách quá trình fusion thành 2 cặp “bimodal” (Text-Visual và Text-Acoustic) thay vì dùng 3 modal song song.
Tận dụng đặc trưng “thông tin mạnh” từ văn bản, đồng thời cho phép kết hợp hình ảnh hoặc âm thanh một cách “bổ sung” (complementation).

Cấu trúc:
Modality Sequence Encoder (BERT, BiGRU).
Modality Complementation Module (chứa GCT + Feature Space Separator).
Output Layer: trộn các đầu ra để dự đoán.
