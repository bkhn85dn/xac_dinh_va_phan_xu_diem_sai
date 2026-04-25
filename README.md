===================25/04===================
File multiview_MDV_from_2json.ipynb đã tích hợp được 2D poses estimation từ 2 video để ra được bộ 3D poses. 
Để chạy được file .ipynb đó, cần tải về thêm file MDVPose.zip tại đây: 
            https://drive.google.com/file/d/1mIxqbVryB9HaJyPDMQF0mq4Zsz-g-g8a/view?usp=drive_link
===================21/04===================
Kết quả của file output là phần nằm ngoài cùng bên phải của video sau 
https://drive.google.com/file/d/1OVQH4nrfSXh3SguXLXYa2vsBKk_D1dpB/view?usp=sharing 

Phần video ngoài cùng bên trái và phần video ở giữa là hai góc nhìn trái phải của hai camera

Kết quả đầu ra vẫn bị rung lắc nhiều, cần tích hợp pipeline khử nhiễu. Ngoài các phương pháp khử nhiễu thông thường, có thể quan tâm đến phương pháp sau:
a fourth-order Butterworth lowpass digital filter with zero-phase shift at 8 Hz was applied, following two papers:

Mizuki Makino and Kenji Tauchi. Kinematic factors related to forward and vertical release velocity in male javelin throwers. International Journal of Sport and Health Science, 20:249–259, 2022

Hiroko Takigawa and Kenji Tauchi. Factors in javelin throw that result in differences in throwing records between throwers with similar approach velocities. International Journal of Sport and Health Science, 21:153–159, 2023
