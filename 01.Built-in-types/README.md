## JavaScript định nghĩa 8 kiểu dữ liệu built-in

| **Type**      | **Giải thích**                                                      |
| ------------- | ------------------------------------------------------------------- |
| **Number**    | Kiểu số dạng floating point theo chuẩn IEEE 754 double-precision.   |
| **String**    | Chuỗi UTF-16 **immutable** (không thể thay đổi sau khi tạo).        |
| **BigInt**    | Kiểu số nguyên với độ chính xác tùy ý (arbitrary precision).        |
| **Boolean**   | Giá trị logic gồm `true` và `false`.                                |
| **Symbol**    | Giá trị duy nhất (unique), thường dùng làm key trong Object.        |
| **Null**      | Đại diện cho “không có giá trị”, tương đương unit type.             |
| **Undefined** | Đại diện cho giá trị chưa được gán, cũng tương đương unit type.     |
| **Object**    | Kiểu dữ liệu dạng cấu trúc, tương tự record (tập hợp các property). |

## Các kiểu dữ liệu quan trọng khác trong TypeScript

| **Type**               | **Giải thích**                                                                                                                 |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **`unknown`**          | Kiểu dữ liệu tổng quát nhất (top type), đại diện cho mọi giá trị nhưng **không thể sử dụng trực tiếp** nếu chưa kiểm tra kiểu. |
| **`never`**            | Kiểu đáy (bottom type), đại diện cho giá trị **không bao giờ tồn tại** (ví dụ: hàm luôn throw error).                          |
| **object literal**     | Kiểu Object được mô tả trực tiếp bằng cấu trúc, ví dụ `{ property: Type }`.                                                    |
| **`void`**             | Dùng cho Function không có giá trị return được mô tả.                                                                          |
| **`T[]` / `Array<T>`** | Array mutable (có thể thay đổi), chứa các phần tử kiểu `T`.                                                                    |
| **`[T, T]`**           | Tuple: Array có **độ dài cố định**, nhưng vẫn mutable.                                                                         |
| **`(t: T) => U`**      | Kiểu Function: nhận tham số kiểu `T`, trả về giá trị kiểu `U`.                                                                 |

