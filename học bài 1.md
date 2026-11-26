
# BÀI 1: QUY TẮC ĐẶT TÊN BIẾN TRONG JAVASCRIPT

## 1. Quy tắc đặt tên biến

### 1.1. Ký tự được phép sử dụng

Tên biến có thể chứa:
- Chữ cái từ `a-z` hoặc `A-Z`.
- Chữ số từ `0-9`.
- Dấu gạch dưới `_`.
- Dấu đô la `$`.

**Ví dụ:**

```javascript
let user1 = "John";
let _name = "David";
let $price = 100;
let userName123 = "Tom";
```

### 1.2. Ký tự bắt đầu

Tên biến có thể bắt đầu bằng:
- Chữ cái (`a-z`, `A-Z`).
- Dấu gạch dưới (`_`).
- Dấu đô la (`$`).

**Lưu ý:** Không được bắt đầu bằng chữ số (`0-9`).

**Ví dụ:**

```javascript
// Hợp lệ
let name = "John";
let _name = "David";
let $name = "Tom";

// Không hợp lệ
let 1name = "John";
let 123user = "David";
```

### 1.3. Không sử dụng từ khóa dành riêng của JavaScript

Không được sử dụng các từ khóa dành riêng làm tên biến.

**Ví dụ:**

```javascript
// Không hợp lệ
let let = 10;
let const = 20;
let class = "Hello";

// Hợp lệ
let Let = 10;
let Const = 20;
let Class = "Hello";
```

**Lưu ý:** JavaScript phân biệt chữ hoa và chữ thường.

### 1.4. Phân biệt chữ hoa và chữ thường

JavaScript có phân biệt chữ hoa và chữ thường (Case-sensitive).

**Ví dụ:**

```javascript
let userName = "John";
let username = "David";

console.log(userName);
console.log(username);
```

`userName` và `username` là hai biến khác nhau.

### 1.5. Không sử dụng khoảng trắng và ký tự đặc biệt

Tên biến không được chứa khoảng trắng hoặc các ký tự đặc biệt như `@`, `#`, `%`, `-`.

**Ví dụ:**

```javascript
// Không hợp lệ
let user name = "John";
let user-name = "David";
let user@name = "Tom";

// Hợp lệ
let userName = "John";
let user_name = "David";
```

## 2. Quy ước đặt tên biến

JavaScript thường sử dụng quy tắc `camelCase`.

- Chữ cái đầu tiên viết thường.
- Các từ tiếp theo viết hoa chữ cái đầu.
- Không sử dụng khoảng trắng.

**Ví dụ:**

```javascript
let firstName = "John";
let lastName = "David";
let userAge = 20;
let totalPrice = 500;
```

## 3. Tổng kết

| Quy tắc | Nội dung |
|---|---|
| Ký tự | `a-z`, `A-Z`, `0-9`, `_`, `$` |
| Ký tự đầu | Chữ cái, `_` hoặc `$` |
| Chữ số đầu | Không được phép |
| Từ khóa JS | Không được sử dụng |
| Khoảng trắng | Không được phép |
| Phân biệt hoa/thường | Có |
| Quy ước nên dùng | `camelCase` |

## 4. Ghi nhớ

> Đặt tên biến ngắn gọn, dễ hiểu và thể hiện đúng dữ liệu mà biến lưu trữ.
