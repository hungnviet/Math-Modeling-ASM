# Math-modeling-assignment
Trình bày thuật toán với C++:
- Input: 
+ The number of Nodes: n			(Số Node của model)
+ The number of Arcs: m			(Số cầu nối)
•	M dòng tiếp theo, mỗi dòng tương ứng số liệu 1 cây cầu
•	1 cây cầu: i, j, cost, capacity 		(Cầu nối từ Node i tới Node j, có chi phí “cost” và sức chứa tối đa “capacity”)
+ The number of Disaster areas: x		(Số điểm thảm hoạ (các source))
•	X dòng tiếp theo, mỗi dòng tương ứng với số liệu của 1 điểm thảm hoạ
•	1 điểm thảm hoạ: i, demand		(Node i là Node source, demand là số người cần di tản)
+ The number of Safe areas: y			(Số điểm an toàn (các sink))
•	Y dòng tiếp theo, mỗi dòng tương ứng với số liệu của 1 điểm an toàn
•	1 điểm an toàn: j, demand 		(Node j là Node sink, demand là số người tiếp nhận)
Sau khi thuật toán xử lý và sẽ cho ra kết quả là chi phí thấp nhất để di tản hết toàn bộ người dân.