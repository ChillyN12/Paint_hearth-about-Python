numpy.linspace(0, 2 * np.pi, 1000) tạo ra 1000 điểm giá trị từ 0 đến 2π cho trục thời gian.
Công thức để vẽ hình trái tim dựa trên phương trình parametric:
x = 16 * np.sin(t) ** 3
y = 13 * np.cos(t) - 5 * np.cos(2 * t) - 2 * np.cos(3 * t) - np.cos(4 * t)
plt.plot(x, y) vẽ đường cong trái tim với màu đỏ (color='red').
plt.axis('off') tắt hiển thị các trục để chỉ tập trung vào hình trái tim.
Chạy mã này sẽ hiển thị một hình trái tim màu đỏ.
