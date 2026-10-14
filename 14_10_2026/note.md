Bài "Top K Frequent Element" có 3 cách làm:
Cách 1: Tạo 1 dictionary rồi duyệt 1 vòng qua list nums, dùng đk if else để đếm tầng suất của từng element, sau đó sorted theo thứ tự rồi in kq
Cách 2: Dùng Min-Heap (Ưu tiên hàng đợi - Priority Queue), đếm tầng suất giống hashmap cách 1 rồi dùng min_heap với kích thước K, 