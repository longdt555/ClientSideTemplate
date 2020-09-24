### Component 
Container: nhận dữ liệu từ server, component này không render và cũng không nhận bất kỳ thao tác nào của người dùng
Presentation: chỉ đảm nhiệm việc render, chỉ nhận dữ liệu thông qua props, không có state
Interactive: nhận các thao tác từ người dùng, component này sẽ khai báo các hàm handleClick, handleChange,…và truyền cho presentation component thông qua props.

--> Với cách tổ chức 3 components như trên thì ưu điểm là phân rõ rạch ròi nhiệm vụ cho từng component: lấy dữ liệu, xuất dữ liệu và tương tác người dùng.

### Cách viết một component React đúng chuẩn ….Airbnb
Tham khảo tại đây: https://github.com/airbnb/javascript/tree/master/react