# CheckTimeLifeCycle
Tạo ứng dụng CheckLifeTimeCycle
Start: onCreate, onStart, onResume
Bấm nút Home: onPause, onStop
Bấm nút Back: onPause, onStop, onDestroyed
Có ứng dụng khác kích hoạt: onPause, onStop
Xoay màn hình: onP, onS, onD, onC, onStart, onRe
Tắt nguồn: onP, onStop

Chọn menu Source/ Override/Implement methods để override các phương thức onStart, onRestart, onResume,onPause, onStop, onDestroy

Trong các hàm trên Viết lệnh hiển thị message cho mỗi sự kiện
Toast.makeText(this,”onResume”, Toast.LENGTH_SHORT).show();
