Array include:

- Static array
  - Fixed size array
  - Allocated trong memory tại compile time
- Dynamic array
  - resizeable array
  - Allocated tron memory tại run time
  - Khi mà array dynamic gần đầy → nó sẽ allocate 1 array mới có kích thước lớn hơn thường là gấp đôi sau đó copy array cũ vào array mới, tương tự với khi delete thì nó sẽ được opy sang array nhỏ hơn
  - Located in heap memory space normally, heap size có thể request tăng lên
  - Python: list - python chỉ có mảng động

Đặc điểm:

- data trong mảng được lưu trữ liên tiếp nhau trên memory
- random access: O(1)
- thêm và xóa phần tử ở `cuối` mảng (chỉ mảng động): `O(1)`
- thêm và xóa 1 phần tử `bất kì` trong mảng: `O(n)`

![time complexity array](../../images/array-time-complex.jpg)

### Advanced

- kadane's algorithm
- sliding window fixed size
- sliding window variable size
- two pointers
- prefix sums
