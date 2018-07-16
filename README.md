# ListView ReactNative Training

# Mục tiêu bài tập
- Biết sử dụng FlatList để tạo ListView
- Biết cách phân trang API để lấy dữ liệu theo từng trang

# Nội dung bài tập

- Sử dụng https://randomuser.me/api để lấy về danh sách user
- Hiển thị danh sách user lấy được qua API
- Khi user vuốt đến trang cuối, sẽ load thêm 20 member khác
- Khi user vuốt ngược lên trên, reload lại danh sách user mới

# Hướng Dẫn Chung
- Đăng ký API https://randomuser.me/api, sử dụng param page, results để phân trang cho danh sách user trả về
- Sử dụng FlatList hiển thị danh sách user
- Sử dụng props renderItem để render ra Item mong muốn, Item có thể là 1 component con
- Sử dụng props onEndReached để loadMore
- Sử dụng onRefresh để reload lại data mới